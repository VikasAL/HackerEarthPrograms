#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>
#define MAX_SCORE 1001
 
int bullet[MAX_SCORE];
int coder[MAX_SCORE];
int prev[MAX_SCORE];
 
int main() {
 
	int N;
	
	scanf("%d",&N);
	int tmp;
	
	for(int i = 0; i < N; i++){
	    scanf("%d", &tmp);
	    bullet[tmp]++;
	    coder[tmp]++;
	}
	
	int current;
	tmp = -1;
	for(int i = 1; i <MAX_SCORE ; i++){
	    if(coder[i] != 0){
	        prev[i] = tmp;
	        current = tmp;
	        tmp = i;
	        
	        while(current != -1 && bullet[i] != 0){
	            
	            if(bullet[i] >= coder[current]){
	                bullet[i] -= coder[current];
	                coder[current] = 0;
	                prev[i] = prev[current];
	            }
	            else{
	                coder[current] -= bullet[i];
	                bullet[i] = 0;
	            }
	            
	            current = prev[current];
	        }
	        
	    }
	}
	int sum;
	
	current = tmp;
	while(current != -1){
	    sum += current * coder[current];
	    current = prev[current];
	}
	
	
	printf("%d",sum);
	
	return 0;
 
}

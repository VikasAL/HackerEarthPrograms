#include <bits/stdc++.h>
 
#define pb push_back
#define ss second
#define ff first
#define N 100005
#define inf 1000000009
#define ll long long
#define mid(a,b) (a+b)/2
 
using namespace std;
 
int n,k,len,x;
map <int,int> m;
pair <int,int> T[N];
 
void pushup(int nd){
	if(nd / 2 >= 1){
		if(T[nd].ss > T[nd / 2].ss){
			m[T[nd].ff] = nd / 2;
			m[T[nd / 2].ff] = nd;
			swap(T[nd],T[nd / 2]);
			pushup(nd / 2);
		}
		else if(T[nd].ss == T[nd / 2].ss and T[nd].ff > T[nd / 2].ff){
			m[T[nd].ff] = nd / 2;
			m[T[nd / 2].ff] = nd;
			swap(T[nd],T[nd / 2]);
			pushup(nd / 2);
		}
	}
}
 
void push(int x){
	if(m[x] == 0){
		len++;
		m[x] = len;
		T[len].ff = x;
		T[len].ss = 1;
		pushup(len);
	}
	else {
		T[m[x]].ss++;
		pushup(m[x]);
	}
}
 
 
int main()
{
	cin >> n >> k;
	for(int i = 1;i <= n;i++){
		cin >> x;
		push(x);
		cout << T[1].ff << " " << T[1].ss << '\n';
	}
}

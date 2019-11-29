#include <bits/stdc++.h>
 
using namespace std;
 
const int N = 1E5 + 5;
bool vis[N];
vector<int> tree[N];
 
int start = -1;
int total = 0;
 
void dfs(int src, int len) {
    vis[src] = true;
    if(len > total) {
        total = len;
        start = src;
    }
    for(auto i : tree[src]) {
        if(!vis[i])
            dfs(i, len + 1);
    }
    return;
}
 
int main() {
    int n;
    cin >> n;
    int a, b;
    for(int i = 0; i < n; i ++) {
        cin >> a >> b;
        tree[a].push_back(b);
        tree[b].push_back(a);
    }
    dfs(1, 1);
    cout << start << ' ';
    total = 0;
    for(int i=0;i<N;i++) vis[i] = false; 
    //memset(vis, false, sizeof vis);
    dfs(start, 1);
    cout << start;
    return 0;
}

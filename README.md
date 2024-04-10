- 👋 Hi, I’m @conjugatehira
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
#include<bits/stdc++.h>
using namespace std;
int main(){
int n,m;
cin>>n>>m;
vector<int>v;

while(n--){
int x;
cin>>x;
v.push_back(x);
}
sort(v.begin(),v.end());
int l=0;
for(int i=0;i<m;i++){

if(v[i]>0){ break;}
else{
 l+=(-1)*v[i];
}
}
cout<<l<<endl;
}

<!---
conjugatehira/conjugatehira is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

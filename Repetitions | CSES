#include<iostream>
#include<vector>
#include<map>
#include<unordered_map>
#include<set>
#include<stack>
#include<queue>
#include<cmath>
#include<math.h>
#include<string>
#include<iterator>
#include<algorithm>
#include<ctype.h>
#include<bits/stdc++.h>
#define BHUSHAN ios_base::sync_with_stdio(0);cin.tie(0);cout.tie(0);
#define ll long long
#define vi vector<ll>
#define vip vector<pair<ll,ll>>
#define yes cout<<"YES"<<endl;
#define no cout<<"NO"<<endl;
using namespace std;
ll factorial(ll n){return (n == 1 || n == 0) ? 1 : n * factorial(n - 1);}
ll max(ll a,ll b){if(a>b)return a;return b;}
void inputv(vector<ll>&v,ll n){for(ll i=0;i<n;i++){ll x;cin>>x;v.push_back(x);}return;}
void coutv(vector<ll>v){for(ll i=0;i<v.size();i++)cout<<v[i]<<" ";cout<<endl;return;}
bool isPowerOfTwo(ll n){if(n==0)return false;return (ceil(log2(n)) == floor(log2(n)));}
bool isPrime(ll n){if (n <= 1)return false;for (int i = 2; i <= sqrt(n); i++)if (n % i == 0)return false;return true;}
int gcd(int a, int b){if (a == 0)return b;return gcd(b % a, a);}ll ceil_div(ll a, ll b) {return a % b == 0 ? a / b : a / b + 1;}
ll mex(vector<ll>v){ll ans=-1;unordered_map<ll,ll>mp;for(ll i=0;i<v.size();i++)mp[v[i]]++;for(ll i=0;i<=v.size();i++){if(mp[i]==0)return i;}}
bool isSorted(vector<ll>v){ ll n=v.size();vector<ll>s;s=v;sort(s.begin(),s.end());for(ll i=0;i<n;i++){if(s[i]!=v[i]){return false;}}return true;}
//***************************************START YOUR CODE FROM HERE******************************************//
// vector<ll>ans;

 ll mod=1000000000+7;
int main()
{
	ll T=1;
//	cin>>T;
    while((T--))
    {
       string s;
       cin>>s;
       ll temp=1;
       ll ans=1;
       for(ll i=1;i<s.size();i++)
       {
       	 if(s[i-1]==s[i])
       	 temp++;
       	 else
       	 {
       	 	ans=max(temp,ans);
       	 	temp=1;
       	 	
			}
	   }
	   ans=max(temp,ans);
	   cout<<ans<<endl;

	}
	 return 0;
}



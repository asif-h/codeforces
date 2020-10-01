# codeforces-problem
151A-soft drink

#include<bits/stdc++.h>

using namespace std;

int main()
{
	int n,k,l,c,d,p,nl,np;
	cin>>n>>k>>l>>c>>d>>p>>nl>>np;
	int a[3];
	a[0]=(k*l)/nl;
	a[1]=p/np;
	a[2]=c*d;
	int totalToast=*min_element(a,a+3)/n;
	cout<<totalToast<<endl;
	return 0;
}
	

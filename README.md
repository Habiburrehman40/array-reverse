#include<iostream>
using namespace std;
int main(){    
	int a[10];    
	int sum=0;    
	for(int b=0;b<=9;b++)
	{    cin>>a[b];    }    
	for(int b=0;b<=9;b++)
	{    if(a[b]!=a[2] && a[b]!=a[4])
	{    sum=sum+a[b];}    }    
	cout<<sum<<endl;   
	for(int b=9;b>=0;b--)
	{    cout<<a[b]<<endl;    }
	return 0;
	}

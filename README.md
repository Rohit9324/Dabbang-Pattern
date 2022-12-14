# Dabbang-Pattern
It is a code of a pattern program in C++.

#include<iostream>
using namespace std;
int main()
{
int n=5;
int i=1;
while(i<=n){
	int j=n;
	int value=1;
	while(j>=i){
		cout<<value;
		value=value+1;
		j=j-1;
	}
	int k=2;
	while(k<=i){
		cout<<"**";
		k=k+1;
	}
	int l=5;
	int values=5-i+1;
	while(l>=i){
		cout<<values;
		values=values-1;
		l=l-1;
	}
	cout<<endl;
	i=i+1;
}
}

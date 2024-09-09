**WEEK 4 : Q=1**
#include<iostream>

using namespace std;

int main() {
	int x;
	string result;
	cout<< " Enter a No. :";
	cin>> x;
	result= (x%2==0) ?"Even" : "Odd";
	cout<< " The number is "<<result ;
	
	return 0;
}

# Reverse-nine-times-table
[ using while loop ]
#include<iostream>
using namespace std;
int main()
{
	int num = 108;   //declaring variable with datatype int and assigning value to it 
	while (num >=9)   //using while-loop 
	{

		cout << num << endl;  
		num = num - 9;  //decreasing the value stored in num by 9 
	}
	cin.get();   
	return 0;
}

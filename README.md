# nameBackCPP
My nameBackwards program converted from C# to C++

#include <iostream>
#include <string>
#include <sstream>

int main()
{
	using namespace std;
	
	cout << "What is your name?" << endl;
	string Name = "";
	getline(Name, cin);
	NameDigits = Name.length;
	cout << "There are " << NameDigits << "digits in your name" << endl;
	
	//separation
	//separation
	//separation
	
	for (int i = NameDigits; i > 0; i = i - 1)
	{
		cout << Name[i - 1] << endl;
	}
	cout << "is your name backwards!");
	
}
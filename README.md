#include<iostream>
#include<vector>
using namespace std;
int main()
{
	vector <int> numbers;
	numbers.push_back(100);
	numbers.push_back(20);
	numbers.push_back(30);
	numbers.push_back(50);
	numbers.push_back(90);
	numbers.push_back(80);
	numbers.push_back(70);
	
	cout << "the first element : " << numbers.front() << endl;
	cout << "last element : " << numbers.back() << endl;
	cout << "the size is " << numbers.size() << endl;
	cout << "the capacity is " << numbers.capacity() <<endl;
	cout << "empty " << numbers.empty();
}

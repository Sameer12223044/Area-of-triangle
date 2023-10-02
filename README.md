# Area-of-triangle in c++
Using default constructor
// WAP to create class rectangle with member l, b initialised with constructor and find area:-
#include<iostream>
using namespace std;
class Rectangle
{
	int l,b;
	public:
		Rectangle()
		{
			l=10;
			b=20;
		}
		void area()
		{
			cout<<"Area is: "<<l*b;
		}
};
main()
{
	Rectangle ob;
	ob.area();
}

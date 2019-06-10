#include <iostream>                   // furkan eken 19540
#include <string>
using namespace std;


#define SIZE 100

// Class for stack
template <class X>
class stack
{
	X *arr;
	int top;
	int capacity;

public:
	stack(int size = SIZE);	// constructor

	void push(X);
	X pop();
	bool isEmpty();
	
	
	
};

template <class X>
stack<X>::stack(int size)
{
	arr = new X[size];
	capacity = size;
	top = -1;
}

// function to add an element x in the stack
template <class X>
void stack<X>::push(X x)
{
	arr[++top] = x;
}

// function to pop top element from the stack
template <class X>
X stack<X>::pop()
{
	// check for stack underflow
	if (isEmpty())
	{
		cout << "UnderFlow\nProgram Terminated\n";
		exit(EXIT_FAILURE);
	}

	

	
	return arr[top--];
}
template <class X>
bool stack<X>::isEmpty()
{
	return top == -1;	// or return size() == 0;
}
template <class X>
void printreverse(stack<X> a)
{
	char b = a.pop();
	if (!a.isEmpty())
	{
		printreverse(a);
	}
	cout << b;
}


int main()
{
	string final;
	string example;   //sit3h4_isa_an_33336a33354444444example!1    //dcaba //  Letz'sa/_h6aazzzve_/a/_good_semester6z6/!!!!1       "I_Love_Str3333344Data_444uctures1"
	stack<char> first;        // note: if u wish u can assingn these to example for check!!
	stack<char> second;
	stack<char> temp;
	cin >> example;
	for (int i = example.length() - 1; i >= 0; i--)
	{
		first.push(example[i]);
	}
	while (!first.isEmpty())
	{
		char a = first.pop();
		if (a == '1')
		{
			break;
		}
		else if (a == '2')
		{
			second.pop();
		}
		else if (a == '3')
		{
			char threefunc;
			threefunc = second.pop();
			temp.push(threefunc);
		}
		else if (a == '4')
		{
			char fourfunc;
			fourfunc = temp.pop();
			second.push(fourfunc);
		}
		else if (a == '5')
		{
			char tempchar;
			stack<char> reversestack;
			while (!second.isEmpty())
			{
				tempchar = second.pop();
				reversestack.push(tempchar);

			}
			second = reversestack;
		}
		else if (a == '6')
		{
			stack<char> tempstack;
			char deletechar = first.pop();
			while (!second.isEmpty())
			{
				char elements = second.pop();
				if (elements != deletechar)
				{
					tempstack.push(elements);
				}
			}
			while (!tempstack.isEmpty())
			{
				char tempelements = tempstack.pop();
				second.push(tempelements);
			}
		}
		else
		{
			second.push(a);
		}

	}
	printreverse(second);
	cin.get();
	cin.ignore();

}

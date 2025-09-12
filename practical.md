// program to use cout and cin
#include <iostream>

using namespace std;

int main()
{
    int u;
    cout<< "Username:";
    cin>> u;
    cout<< u+10;
    cout<< u; 
    return 0;
}


// program to understand prefix and postfix
#include <iostream>

using namespace std;

int main()
{
    int a=5;
    int b;
    b= ++a ;
    cout<< a;
    cout<<b;
    a=5;
    b=a++;
    cout<<a;
    cout<<b;
    b=--a;
    cout<<a;
    cout<<b;
    b=a--;
    cout<<a;
    cout<<b;
    return 0;
}

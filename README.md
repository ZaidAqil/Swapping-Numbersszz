# Swapping-Numbersszz
//Zaids Programme Page 79 Question 2
#include <iostream>
#include <string>
using namespace std;

void swap(float,float);

int main()
{
    float a, b;
    cout<<"Enter two values:"<<endl;
    cin>>a>>b;
    cout<<"The original paor is:"<<endl;
    cout<<"a=" <<a <<" ,b="<<b<<endl;
    swap (a,b);
    return 0;
}
void swap(float a, float b )
{
    cout<<"After swapping:"<<endl;
    cout<<"a="<<b<<" ,b="<<a<<endl;
}

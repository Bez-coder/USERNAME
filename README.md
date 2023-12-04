#include <iostream>
using namespace std;
int main()
{
 int choice;

 cout<<"What do u want to do?"<<endl;
 cout <<" Enter your choice "<<endl;
 cin>>choice;
 switch(choice){
    int x,y,z;
     case 1:cout<<"Enter your number ";
     cin>>x;
     if(x>=0)
        cout<<x<<" is positive";
     else
        cout<<x<<" is negative";
        break;
     case 2:cout<<"Enter your number ";
     cin>>x;
     if(x%2==0)
        cout<<x<<" is even";
     else
        cout<<x<<" is odd";
        break;
     case 3:cout<<"Enter your first number "<<endl;
     cin>>x;
     cout<<"Enter your number ";
     cin>>y;
     cout<<"Enter your number ";
     cin>>z;
     if(x>y && y>z)
        cout<<x<<" is the largest number";
     else if(y>x &&x>z)
        cout<<y<<" is the largest number";
     else
        cout<<z<<" is the largest number";
        break;
        }
    return 0;
    }

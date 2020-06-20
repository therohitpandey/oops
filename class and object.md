#include<iostream.h>
#include<conio.h>
class example
{
int a,b,c;
public:
void get()
{
cout<<"enter value of a and b"<<endl;
cin>>a>>b;
}
void sum()
{
c=a+b;
}
void show()
{
cout<<"sum of a and b is"<<c;
}
};
void main()
{
clrscr();
example e,e1;
cout<<"\nsolution for object e"<<endl;
e.get();
e.sum();
e.show();
cout<<"\nsolution for object e1"<<endl;
e1.get();
e1.sum();
e1.show();
getch();
}

#include <iostream>
#include<conio.h>
using namespace std;
class ParentClass 
{
  public:
    int var1 =100;
}
;
class ChildClass: public ParentClass
{
  public:
  int var2 = 500;
};
int main(void)
{
  ChildClass obj;
}

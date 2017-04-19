# HelloWorld
primary programming
#include <iostream>
#include <list>
using namespace std;

int main()
{
  list<student> Mylist;
  struct student
  {
    int age;
    char name[10];
  };
  student a1, a2;
  a1.age = 12;
  a1.name = "wang";
  a2.age = 14;
  a2.name = "zhang"
  Mylist.push_back(a1);
  Mylist.push_back(a2);
  return 0;
}

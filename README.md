# hello-world
jast a test
#include <iostream>
using namespace std;
class Test
{
public:
  char getname();
  void setname(char);
private:
  char name;
}

Test::getname()
{
  return name;
}

Test::setname(char x)
{
name=x;
}

int main()
{
char y="thert";
Test test;
test.setname(y);
cout << test.getname() << endl;
}

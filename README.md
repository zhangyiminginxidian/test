#include <iostream>
#include <list>
 using namespace std;
 int main()
{
  list<string> qko;
  qko.push_back("梁尼玛");
  qko.push_back("王尼玛");
  qko.pop_back(); 
 list<string>::iterator iter=qko.begin();
 while(iter!=qko.end())
 {
 	cout<<*iter;
 	iter++;
 }
}

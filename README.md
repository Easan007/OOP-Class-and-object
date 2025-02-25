#include <iostream>
using namespace std;

class Myfunction
{
    public :
    int age;
    int Class;
    int number;
};
int main()
{
  Myfunction Atik;  
  Atik.age = 19;
  Atik.Class = 9;
  Atik.number = 24590453;
  
  cout<<"Atik's Age : " <<Atik.age <<endl;
  cout<<"Atik's Class : " <<Atik.Class <<endl;
  cout<<"Atik's Number : " <<Atik.number <<endl;
}

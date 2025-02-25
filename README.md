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
  
  Myfunction Ananya;
  Ananya.age = 20;
  Ananya.Class = 10;
  Ananya.number = 23980454;
  
  cout<<"Atik's Age : " <<Atik.age <<endl;
  cout<<"Atik's Class : " <<Atik.Class <<endl;
  cout<<"Atik's ID Number : " <<Atik.number <<endl;
  
  cout<<"Ananya's Age : "<<Ananya.age <<endl;
  cout<<"Ananya's Class : "<<Ananya.Class <<endl;
  cout<<"Ananya's ID Number : "<<Ananya.number <<endl;
}

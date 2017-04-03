# Placeholder
Practicing classes/inheritance 
#include <iostream>
using namespace std;

class student{
  string lastName;
  string firstName;
  int classYear;
  string major; 
  void getStudent (string lastName,string firstName,int classYear,string major){
    this.firstName=firstName;
    this.lastName=lastName;
    this.classYear=classYear;
    this.major=major;
  }
}
int main() {
  student student1;
  student student2;
  student1.getStudent("Jenkins","Bob",3,"Arts");
  student2.getStudent("Wang","Olga",4,"Math");
}

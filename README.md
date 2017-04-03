# Class-Practice-1
Practicing classes/inheritance 
#include <iostream>
using namespace std;

class student{
  string lastName, firstName;
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
  student student[];
  student[0].getStudent("Jenkins","Bob",3,"Arts");
  student[1].getStudent("Wang","Olga",4,"Math");
  for (i=0; i<2; i++){
    cout<<"Student Number 0000000"<<i<<": "<<student[i].lastName<<", "<<student[i].firstName<<endl<<
    "Class year: "<<student[i].classYear<<student[i].<<endl<<
    "Major: "<<student[i].major<<endl;
  }
  return 0;
}

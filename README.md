# calculatenetsalary

#include <iostream>

using namespace std;

int main()

{
     
float basic ;

float percentAllow;

float percentdeduct;

float netsalary;

cout<<"Enter basic salary:";

cin>>basic;

cout<<"Enter percent of Allowances:";

cin>>percentAllow;

cout<<"Enter percent of deductions:";

cin>>percentdeduct;

netsalary= basic+basic*percentAllow/100-basic*percentdeduct/100;

cout<<"Net salary is"<<net salary<<endl;
 
 return 0;
}


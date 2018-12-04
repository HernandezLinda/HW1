# HW1
/ Name: Linda Hernandez
// Date: 9/18/2018
// Assignment: Malachi's Pie Shop HW1
// Class: COP2000 TR 6:30
// This program calculates the correct recipe for six pie crusts.
#include <iostream>
#include <iomanip>
using namespace std;

int main()
{
    // Defining variables
   double flour, sugar, salt, eggs, butter, pies;
   
   flour = 15.00;
   butter = 5.25;
   sugar = 8.00;
   salt = 3.00;
   eggs = 6.00;
   pies = 6.00;

   // Num. of pies
   cout <<"Welcome to Malachi's Pie Shop." << endl;
   cout <<"How many pie would you like to make?" << endl;
   cout << pies << endl;
   cout <<"__________________________________________________________" << endl;
   // Ingredients
   cout <<"With this recipe one has the ability to make 6 pie crusts." << endl;
   cout <<"The ingredients that are required are... " << endl;
   cout << flour << "cups of flour" << endl;
   cout << butter << "cups of butter" << endl;
   cout << sugar << "tablespoons of sugar" << endl;
   cout << salt << "tablespoons of salt" << endl;
   cout << eggs << "large eggs" << endl;
   cout <<"__________________________________________________________" << endl;
   // Calculation for one pie crust
   cout << "The recipe for" << pies / 6 << "pie crust as requested is..." << endl;
   cout << flour / 6 << "cups of flour." << endl;
   cout << butter / 6 << "cups of butter" << endl;
   cout << sugar / 6 << "tablespoon of sugar" << endl;
   cout << salt / 6 << "tablespoon of salt" << endl;
   cout << eggs / 6 << "large egg" << endl;
   cout << "_________________________________________________________" << endl;
   

   return 0;
}

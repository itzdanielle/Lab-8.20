# Lab-8.20
#include <iostream>
#include <string>
using namespace std;
int main() {
string name;
string theme;
string place;
string dayOfWeek;
string  time;
string  verb;
string  animal;
string bodyPart;
cout << "His or Her's First Name\n"; 
cin >> name;
cout << "Your favorite theme (one word)\n";
cin >> theme;
cout << "Your favorite place (one word)\n";
cin >> place;
cout << "Your favorite day of the week\n";
cin >> dayOfWeek;
cout << "Your favorite time of the day (one word)\n";
cin >> time;
cout << "Input a verb\n";
cin >> verb;
cout << "Your favorite animal\n";
cin >> animal;
cout << "Input a body part\n";
cin >> bodyPart;
cout << name << " is having a " << theme << " party! It is going to be at the " << endl;
cout << place << " on a " << dayOfWeek << ". Please make sure to show up around the " << endl;
cout << time << ", or else you will be required to " << verb << " on a/an " << endl;
cout << animal << " with your " << bodyPart << "." << endl;

}

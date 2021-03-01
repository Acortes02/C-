# C++
#include <iostream>

using namespace std;
      int main () {
          int age;
          cout << " Please enter your age: " << endl;

          cin >> age;

          if (age < 17) {
              cout << age << " is to young." << endl;
          } else if (age > 37) {
              cout << age << " is too old." << endl;
          } else {
              cout << age << " is the right age." << endl;
          }
          return 0;

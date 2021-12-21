# S2-RESUBMISSION
Marks  25:  
Timings  1  hour  30min   Code  description: Create  a  program  that  asks  the  user  to  input  the  full  name  and  a  number  between  1  to  10  and  print  the following  for  that  number: 
1. Factorial 
2. Table having  a range  of 20-30:   
3. Square and  cube  of that  number 
```
#include <iostream>
#include <string>
using namespace std;
int main()
{
    string fullname;
    cout << "Please enter your full name: " << endl;
    getline(cin, fullname);
	{
		int a, b = 1;
		cout << "Enter a number from 1-10 to factor, find the range from 20-30, find the square root, and cube root of: " << endl;
		cin >> a;
		while (cin.fail() || a <= 0)
		{
			cout << "Number pls! " << endl;
			cin.clear();
			cin.ignore(1000, '\n');
			cin >> a;
		}
		int range = 30;
		cout << "\n";
		cout << fullname << " here are your results:" << endl;
		for (int c = 1; c <= a; c++)
			b = b * c;
		{
			cout << "Factorial: " << b << endl;
			cout << "Range from 20-30 is: " << endl;
		}
		for (int i = 20; i <= range; ++i) {
			cout << a << " * " << i << " = " << a * i << endl;
		}
		cout << "Square root of " << a << " is " << sqrt(a) << endl;
		cout << "Cube root of " << a << " is " << cbrt(a) << endl;

		return 0;
	}
}
```
Ms. I made this because I was unsure if I passed or failed my previous score was 12/25 and I had the resubmission link in my Studylab.
```
EDIT: 12 / 21 / 2021 (2:57PM) NOTE: Count this one as a practice for myself
(\_/)
('_')
(> <)
 U U
 ```

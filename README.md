# Bitwise-Operations-
##IS - First Course 2023

### Task - Even or Odd
Напишете задача, която чрез побитови операции определя дали е четно или нечетно.
```
#include <iostream>
using namespace std;

void EvenOrOddBitwise(int n) {

	int mask = 1;

	if ((mask & n) == 0)
	{
		cout << "Even";
	}
	else
	{
		cout << "Odd";
	}
	
}

int main()
{
	int n;
	cin >> n;
    EvenOrOddBitwise(n);

	return 0;
}
```


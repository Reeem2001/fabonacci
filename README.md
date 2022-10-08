![Fabonacci number sequence](https://s3.studytonight.com/curious/uploads/pictures/1636961595-79542.jpg)

1. Reem Adel
2. sec 1
3. BN24

[Fabonacci Number](https://en.wikipedia.org/wiki/Fibonacci_number)
# fabonacci sequence
## fabonacci sequence
### fabonacci sequence
*fabonacci sequence*

**fabonacci sequence**

|Name      | Email         |
|----------|---------------|
|Reem      |reemadel5004@gmail.com|
|Reem      |Reem.Hamid01@eng-st.cu.edu.eg|

```C++
#include <iostream>
using namespace std;
int main() {
    int n, x1 = 0, x2 = 1, nextx = 0;
    cout << "Enter n: ";
    cin >> n;
    cout << "nth number: ";
    for (int i = 1; i <= n; ++i) {

        if (i == 1 || i == 2) {
            continue;
        }
        nextx = x1 + x2;
        x1 = x2;
        x2 = nextx;
    }
    cout << nextx <<endl;
    return 0;
}
```

```C++
#include<iostream>;
using namespace std;
int main()
{
	int n;
	cout << "Enter N: ";
	cin >> n;

	int* A = new int[n];
	for (int j = 0; j < n; j++)
	{
		if (j == 0 || j == 1)
		{
			A[j] = j;
			continue;
		}
		A[j] = A[j - 1] + A[j - 2];

	}

	cout << A[n - 1] << endl;
	delete[]A;
	return 0;
}
Time complexity: O(n)
Auxiliary space: O(n)



```
```C++
#include <bits/stdc++.h>
using namespace std;
 
int fib(int n)
{
    if (n <= 1)
        return n;
    return fib(n - 1) + fib(n - 2);
}
 
int main()
{
    int n = 9;
    cout << fib(n);
    getchar();
    return 0;
}
space complexity : O(1)
time complexity : Exponential
```



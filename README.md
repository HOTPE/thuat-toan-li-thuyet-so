#include <iostream>
#include <cmath>
using namespace std;
bool isPowerOfTwo(int n)
{
	return n > 0 && ((n & (n - 1)) == 0);
}
int main()
{
	int n;
	cin >> n;
	if (isPowerOfTwo(n))
		cout << "true" << endl;
	else
		cout << "false" << endl;
}

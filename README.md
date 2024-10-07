#include <iostream>

using namespace std;

int main() 
{
	float amount, converted;
	float rate = 56.85;
	
	cout << "Enter amount in USD: ";
	cin >> amount;
	
	converted = amount * rate;
	cout << amount << " USD is equal to " << converted << " PHP" << endl;
	
	cout << "Enter amount in PHP: ";
	cin >> amount;
	
	converted = amount / rate;
	cout << amount << " PHP is equal to " << converted << " USD" << endl;
	
	return 0;
}

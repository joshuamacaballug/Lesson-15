# Lesson-15
// Lecture 15 (Returning values - Purchase products).cpp : This file contains the 'main' function. Program execution begins and ends there.
//

#include <iostream>
using namespace std;

double sumItems(double item1, double item2) {
	double total = item1 + item2;
	return total;
}
int main() {
	
	double myMoney = 40.00;
	double shoes, tshirt;
	cout << "Enter the amount for shoes: " << endl;
	cin >> shoes;
	cout << "Enter the amount for tshirt: " << endl;
	cin >> tshirt;

	if (sumItems(shoes, tshirt) <= myMoney) {
		cout << "you can afford these items" << endl;
	}
	else {
		cout << "keep saving up" << endl;
	}
}

// Run program: Ctrl + F5 or Debug > Start Without Debugging menu
// Debug program: F5 or Debug > Start Debugging menu

// Tips for Getting Started: 
//   1. Use the Solution Explorer window to add/manage files
//   2. Use the Team Explorer window to connect to source control
//   3. Use the Output window to see build output and other messages
//   4. Use the Error List window to view errors
//   5. Go to Project > Add New Item to create new code files, or Project > Add Existing Item to add existing code files to the project
//   6. In the future, to open this project again, go to File > Open > Project and select the .sln file

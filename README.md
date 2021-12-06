# 4
#include <iostream>
#include <string>
using namespace std;

int main()
{

	string snacks[3][4] = {
		{"Galaxy silk", "Mars Bar", "Snickers", "Bounty"}, //first row
		{"Flavoured Yoghurt", "Omen chips", "Oreo", "Lays"}, //second row
		{"Apple", "Banana", "Orange", "Pear"} // third row
	};

	for (int i = 0; i < 3; i++) {
		for (int j = 0; j < 4; j++) {
			cout << snacks[i][j] << " ";
		}
		cout << endl;
	}
}

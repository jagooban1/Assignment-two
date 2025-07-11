# Assignment-two
Arrays
#include <iostream>
using namespace std;

int main() {
    int arr[10]; // static array of size 10

    // Populate the array with user input
    cout << "Enter 10 integers:" << endl;
    for (int i = 0; i < 10; ++i) {
        cin >> arr[i];
    }

    // Print all values
    cout << "Array values:" << endl;
    for (int i = 0; i < 10; ++i) {
        cout << arr[i] << " ";
    }
    cout << endl;
    return 0;
}

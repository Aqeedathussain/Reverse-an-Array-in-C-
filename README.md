### Array Input and Reverse Printing

**Description:**  
This program demonstrates how to take user input for an array and then print the array elements in reverse order. It helps beginners understand arrays, loops, and input/output operations in C++.

**Features:**
- Takes input from the user for a fixed-size array.
- Prints the array elements in reverse order.
- Demonstrates the use of `for` loops and `cin`/`cout` for input and output.

**Code Snippet:**
```cpp
#include <iostream>
using namespace std;

int main() {
    int arr[5];
    cout << "Please enter the values of the array: ";
    for (int i = 0; i < 5; i++) {
        cin >> arr[i];
    }

    for (int i = 4; i >= 0; i--) {
        cout << "The updated array is " << arr[i] << endl;
    }
    return 0;
}

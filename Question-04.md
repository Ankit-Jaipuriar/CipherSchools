```cpp
#include <iostream>
#include <vector>
using namespace std;

int main() {
    using namespace std;
    vector<int> dynamicArray;

    cout << "Enter the number of elements you want to store: ";
    int n;
    cin >> n;

    cout << "Enter " << n << " elements: \n";
    for (int i = 0; i < n; ++i) {
        int element;
        cout << "Element " << (i + 1) << ": ";
        cin >> element;
        dynamicArray.push_back(element);
    }

    cout << "\nElements in the vector are: ";
    for (int element : dynamicArray) {
        cout << element << " ";
    }
    cout << "\n";

    cout << "Enter a new element to add to the vector: ";
    int newElement;
    cin >> newElement;
    dynamicArray.push_back(newElement);

    cout << "\nUpdated elements in the vector are: ";
    for (int element : dynamicArray) {
        cout << element << " ";
    }
    cout << "\n";

    return 0;
}
```

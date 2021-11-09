# Descending 7 Stars, 7 Lines
```
#include <iostream>
using namespace std;
int main()
{
    for (int y = 0; y < 7; y++) {
        for (int x = y; x < 7; x++) {
            cout << "*";
        }
        cout << endl;
    }
    return 0;
}
```

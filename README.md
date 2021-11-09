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
# Rising Stars, 7 Lines
```
#include <iostream>
using namespace std;
int main()
{
    for (int y = 1; y <= 7; y++) {
        for (int x = 1; x <= y; x++) {
            cout << "*";
        }
        cout << endl;
    }
    return 0;
}
```
# Rising and Falling Stars
```
```

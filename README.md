# Lecture 10, Slide 10, Some Counting
```
```
#Lecture 10, Slide 12, Iterate through a word
```
```
# 7 Stars, 7 Lines
```
#include <iostream>
using namespace std;
int main()
{
    for (int i = 0; i < 7; i++) {
        for (int j = 0; j < 7; j++) {
            cout << "*";
        }
        cout << endl;
    }
    return 0;
}
```
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
#include <iostream>
using namespace std;
int main()
{
    for (int y = 1; y <= 7; y++) {
        for (int x = 1; x <= y; x++) {
            cout << "*";
        } cout << endl;
    }
    for (int y = 0; y < 6; y++) {
        for (int x = y; x < 6; x++) {
            cout << "*";
        } cout << endl;
    }
        return 0;
}
```
# Cubes
```
```
# Find the 9s
```
```

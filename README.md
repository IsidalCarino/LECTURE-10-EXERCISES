# Lecture 10, Slide 10, Some Counting
#1 to 50 increments of 1
```
#include <iostream>
using namespace std;
int main()
{
    cout << "1 to 50 Increments of 1\n\n";
    for (int x = 1; x <= 50; x++) {
        cout << x << "\n";
    }
    return 0;
}
```
#50 to 1 decrements of 1
```
#include <iostream>
using namespace std;
int main()
{
    cout << "50 to 1 decrements of 1\n\n";
    for (int x = 50; x >= 1; x--) {
        cout << x << "\n";
    }
    return 0;
}
```
#30 to 50 increments of 1
```
#include <iostream>
using namespace std;
int main()
{
    cout << "30 to 50 Increments of 1\n\n";
    for (int x = 30; x <= 50; x++) {
        cout << x << "\n";
    }
    return 0;
}
```
#50 to 10 decrements of 2
```
#include <iostream>
using namespace std;
int main()
{
    cout << "50 to 10 decrements of 2\n\n";
    for (int x = 50; x >= 10; x-=2) {
        cout << x << "\n";
    }
    return 0;
}
```
#100 to 200 increments of 5
```
#include <iostream>
using namespace std;
int main()
{
    cout << "100 to 200 Increments of 5\n\n";
    for (int x = 100; x <= 200; x+=5) {
        cout << x << "\n";
    }
    return 0;
}
```
# Lecture 10, Slide 12, Iterate through a word
```
#include <iostream>
#include <string>
using namespace std;
int main()
{
    string myWord = "ARSH";
    cout << myWord.at(0) << endl << myWord.at(1) << endl << myWord.at(2) << endl << myWord.at(3) << endl;
}
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
#include <iostream>
using namespace std;
int main()
{
    int x, y, z;
    cout << "Input number (it will find it's cube): \n";
    cin >> y;
    for (x = 1; x <= y; x++)
    {
        z = x * x * x;
        cout << "Number is " << x << " and the cube of " << x << " is " << z << endl;
    }
}
```
# Find the 9s
```
```

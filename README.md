#include <iostream>
using namespace std;

int main() {
    int n = 5; // height of the pyramid
    for (int i = 1; i <= n; ++i) {
        // print spaces
        for (int s = 0; s < n - i; ++s) cout << ' ';
        // print stars
        for (int j = 0; j < i; ++j) cout << '*';
        cout << '\n';
    }
    return 0;
}

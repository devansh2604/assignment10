#include <iostream>
#include <unordered_set>
using namespace std;

int main() {
    int A[] = {1, 2, 3, 4};
    int B[] = {3, 4, 5, 6};

    unordered_set<int> s(A, A + 4);

    cout << "Common Elements: ";
    for (int i = 0; i < 4; i++) {
        if (s.count(B[i])) {
            cout << B[i] << " ";
        }
    }
    return 0;
}

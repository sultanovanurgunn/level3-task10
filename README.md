# level3-task10
#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Nece element istediyinizi daxil edin: ";
    cin >> n;

    int a = 0, b = 1, c;

    cout << "Fibonacci ardicilligi: ";

    for (int i = 1; i <= n; i++) {
        cout << a << " ";
        c = a + b;
        a = b;
        b = c;
    }

    cout << endl;
    return 0;
}

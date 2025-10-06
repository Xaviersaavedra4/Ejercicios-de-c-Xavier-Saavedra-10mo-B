#include <iostream>
using namespace std;

int main() {
    int N1;

    cout << "Ingresar el numero: ";
    cin >> N1;

    if (N1 % 2 == 0) {
        cout << "El numero es par" << endl;
    } else {
        cout << "El numero es impar" << endl;
    }

    return 0;
}

#include <iostream>

using namespace std;

int main() {
    int n;

    cout << "Введите высоту треугольника: ";
    cin >> n;

    for (int i = 1; i <= n; ++i) {
        // Вывод пробелов
        for (int j = 1; j <= n - i; ++j) {
            cout << " ";
        }
        // Вывод звездочек
        for (int j = 1; j <= 2  i - 1; ++j) {
            cout << "";
        }
        cout << endl;
    }

    return 0;
}

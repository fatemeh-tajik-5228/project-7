# project-7
#include <iostream>
using namespace std;
// matris mojaverat ra gerefte va motamam chap beshe
int main() {
	int n ;
    cout << "andaze matris ra vared konid: " ;
    cin >> n ;
    int matris[n][n];
    
    for (int i = 0; i < n ; i++) {
        cout << "Satr " << i + 1 << ": ";
        for (int j = 0; j < n ; j++) {
            cin >> matris[i][j];
        }
    }
    cout << endl;
    
    for (int i = 0; i < n; i++) {
        for (int j = 0; j < n; j++) {
            cout << !matris[i][j] << " ";
        }
        cout << endl;
    }
}

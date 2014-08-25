int
===
#include<iostream>
#include<stdlib.h>
using namespace std;

int main (){
    int a, b;
    cout<< "Digite dois numeros inteiros: ";
    cout<< "\n";
    cin >> a >> b;
    if ( a  > b ) cout << a << "\n" << "\n\n EH O MAIOR \n\n";
    else if ( a < b) cout << b<< "\n" << "\n\n EH O MAIOR \n\n";
    else   cout << "\nESTES NUMEROS SAO IGUAIS. \n";
    system ("pause");

    return 0;

}

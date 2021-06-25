
#include <iostream>
#include <locale.h>
#include <cstdlib>
using namespace std;
int main (){
	int l, c, linha, coluna;
char opc
	inicio: 
	system ("cls");
	setlocale(LC_ALL,"Portuguese");
	cout << "Movimentos de uma Torre no xadrez!\n";
	cout << "\nDigite a linha em que a Torre se encontra: ";
	cin >> linha;
	cout << "\nDigite a coluna em que a Torre se encontra: ";
	cin >> coluna;
	cout << "\nMovimentos possiveis:\n\n";
	cout << "  1  2  3  4  5  6  7  8  \n";
	cout << "  ------------------------\n";
	for (l=1;l<=8;l++){
	cout << l;
	for (c=1;c<=8;c++){
		if (l == linha || c == coluna){
		cout << " x ";
	}else{
		cout << " - ";
	}	
}
	cout << "\n";
	}
	cout << "\n Digitar outras coordenadas?(s/n): ";
	cin >> opc;
	if(opc == 's' or opc == 'S'){
		goto inicio;
return 0;
}
}

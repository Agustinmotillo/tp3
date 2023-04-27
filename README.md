#include <bits/stdc++.h>

using namespace std;

int EstMayor(int a1 ,int a2 ,int a3);

int main(){
	int a1,a2,a3;
	
	cout<<"Ingrese tres numeros: "<<endl;
	cin>>a1>>a2>>a3;
	
	cout<<"El numero mas grande que ingreso es el: "<<EstMayor(a1,a2,a3);
	
	return 0;
	}

int EstMayor(int a1 ,int a2 ,int a3){
	int mayor;
	if(a1<a2 && a1<a3){
		mayor=a1;
	}
		if(a2<a1 && a2<a3){
		mayor=a2;
	}
		if(a3<a2 && a3<a1){
		mayor=a3;
	}
}

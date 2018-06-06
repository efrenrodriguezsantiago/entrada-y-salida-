// esntrada y salida de datos


/* realiza un programa que lea de la entrada estandar los siguientes datos de una persona

    edad: dato de ipo entero
    sexo: de tipo caracter
    estatura: dato de tipo real 
    
    trasleer los datos, el programa debe mostrarlos en la salida estandar 
*/

#include <iostream>

using namespace std;
int main(){
	
	int edad; //la entrada sera de tipo entero
	char sexo[10];  //tipo cadena
	float estatura;  //tipo flotante
	
	cout<<"introduce la edad:";cin>>edad;  //te pide la edad
	cout<<"introduce el sexo:";cin>>sexo;  //te pide que digites el sexo de la persona
	cout<<"introduce la estatura";cin>>estatura;  //te pide la estatura de la persona
	
	
	cout<<"\nla edad es:"<<edad; //aqui imprimira la edad
	cout<<"\nel sexo es:"<<sexo;  //la funcion sera imprimir el sexo
	cout<<"\nla estatura es:"<<estatura;  //imprimira lo que es la estatura...
		
	
	
	return 0;
}

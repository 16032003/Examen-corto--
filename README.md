
#include <iostream>
#include <fstream>
usar el espacio de nombres std;


int main()
{int i=0,j=0;
	char linea[100];
    string palabra=" ";
    cout<<"ingrese palabra "<<endl;
    cin >> palabra;
    for(i=0;i<palabra.length();i++){
        for(j=palabra.length()-1;j>=0;j--){
            if(palabra[i]==palabra[j]){
                cout<<"es palindroma "<<endl;
            }
            else{
                cout<<"no lo es "<<endl;
ofstream archivo_salida("archivo.txt");
archivo_salida << palabra<< endl; 
cout << palabra;
archivo_salida.close();                   
retorno 0;
}
}
}
}

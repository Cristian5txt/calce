#include <iostream>

using namespace std;

int main()
{
    string nombre, apellido1,apellido2, nacionalidad,fecha_nacimiento,lugar_nacimiento,NUM,sexo;
    cin>>nombre;
    cin>> apellido1;
    cin>> apellido2;
    cin>>nacionalidad;

    cout <<"CEDULA DE"<<" ****** " <<"REPUBLICA DEL ECUADOR"<<endl;
    cout<<"IDENTIDAD" <<" ****** " <<"DIRECCION GENERAL DE REGISTRO CIVIL,IDENTIFICACION Y CEDULACION"<<endl;

    cout << "APELLIDOS"<< "        "<< "CONDICON CIUDADANIA*NNA"<<endl;
    cout<< apellido1<<endl;
    cout<< apellido2<<endl;
    cout<< "NOMBRES"<<endl;
    cout<<nombre<<endl;
    cout<< "NACIONALIDAD"<<endl;
    cout<< nacionalidad;
    cout<< "FECHA DE NACIMIENTO"<< "                   "<<"SEXO"<<endl;
    cin>> fecha_nacimiento;
    cout<< "LUGAR DE NACIMIENTO"<< "                   "<<"No.DOCUMENTACION"<<endl;
    cin>> lugar_nacimiento;
    cout<< "   "<<endl;
    cout<< "FIRMA DEL TITULAR"<<endl;
    cout<< "***********"<<endl;
    
    string dia;
    cout<< "INGRESE EL DIA DE LA SEMANA"<<endl;
    switch (dia){
    case 'lunes':
    cout<< "ACCIONES DEL LUNES"<<endl;
    break;
    case 'MARTES':
    cout<< "ACCIONES DEL MARTES"<<endl;
    break;
    }



    return 0;
}

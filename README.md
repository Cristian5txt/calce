#include <iostream>

using namespace std;

int main()
{
string nombre1,nombre2, apellido1,apellido2, nacionalidad,fecha_nacimiento,lugar_nacimiento1,lugar_nacimiento2,NUM,sexo,NUI,fecha_vencimiento;
cout<< "apellidos"<<endl;
cin>>apellido1;
cin>>apellido2;
cout<< "NOMBRES"<<endl;
cin>>nombre1;
cin>>nombre2;
cout<< "Nacionalidad"<<endl;
cin>>nacionalidad;
cout<< "fecha de nacimiento"<<endl;
cin>>fecha_nacimiento;
cout<< "sexo"<<endl;
cin>>sexo;
cout<< "lugar nacimiento"<<endl;
cin>>lugar_nacimiento1;
cin>>lugar_nacimiento2;
cout<< "No Documento"<<endl;
cin>>NUM;
cout<< "FECHA DE VENCIMIENTO"<<endl;
cin>>fecha_vencimiento;
cout<< "NUI"<<endl;
cin>>NUI;

cout<< "    "<<endl;


cout <<"CEDULA DE"<<" ****** " <<"REPUBLICA DEL ECUADOR"<<endl;
cout<<"IDENTIDAD" <<" ****** " <<"DIRECCION GENERAL DE REGISTRO CIVIL,IDENTIFICACION Y CEDULACION"<<endl;

cout << "APELLIDOS"<< "        "<< "CONDICON CIUDADANIA*NNA"<<endl;
cout<< apellido1<<endl;
cout<< apellido2<<endl;
cout<< "NOMBRES"<<endl;
cout<<nombre1<<endl;
cout<<nombre2<<endl;
cout<< "NACIONALIDAD"<<endl;
cout<< nacionalidad<<endl;
cout<< "FECHA DE NACIMIENTO"<< "                        "<<"SEXO"<<endl;
cout<< fecha_nacimiento<<"                                  "<<sexo<<endl;

cout<< "LUGAR DE NACIMIENTO"<< "                        "<<"No.DOCUMENTACION"<<endl;
cout<<lugar_nacimiento1<<"                                  "<<NUM<<endl;
cout<<lugar_nacimiento2<<"                                 "<<"FECHA DE VENCIMIENTO"<<endl;
cout<< "                  FIRMA DEL TITULAR"<< "        "<<fecha_vencimiento<<endl;
cout<< "NUI."<<NUI<<"    *****************       "<<endl;


return 0;

}

#include <iostream>

using namespace std;

int main()
{
    float Vfoco, R, I;
    int V_fuente=12;

    cout<<"INGRESE EL VALOR DEL VOLTAJE DEL FOCO"<<endl;
    cin>>Vfoco;
    cout<< "INGRESE EL VALOR DE LA RESISTENCIA DEL FOCO"<<endl;
    cin>>R;

    I = (V_fuente-Vfoco)/R;
    cout<< "SU VALOR DE LA CORRIENTE ES: "<<I<<endl;

    if (I<=0){
    cout<< "CORTO CIRCUITO"<<endl;
    }
      else if (I==0.5){
         cout<< "CAMBIAR LA RESISTENCIA"<<endl;
    }
          else if (I>1){
             cout<< "FUNCIONA CORRECTAMENTE"<<endl;
    }
                else;
    return 0;
}

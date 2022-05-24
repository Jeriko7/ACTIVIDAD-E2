# PROGRAMAS EN C++ DE GRANJA ESTEFANIA
# Informacion del Autor
Autor: Granja Jaramillo Estefania Lizbeth

Correo: estefania.granja.jaramillo@utelvt.edu.ec

Enlace del video: https://youtu.be/KZkVazWaNMI

# Progamas

=>GranjaEstefania-Compara.cpp 
=>GranjaEstefania-CuentaMoneda.cpp
=>GranjaEstefania-PuntoVenta.cpp
=>GranjaEstefania-SumaN.cpp
=>GranjaEstefania-laedad.cpp

# Descripcion de los Programas
### GranjaEstefania-Compara.cpp
Este programa en c++ permite comparar dos numeros y determinar si son igual o cual es mayor.

### GranjaEstefania-CuentaMoneda.cpp
Este programa en c++ permite calcular el total de monedas ingresadas y la cantidad de sus denominaciones.

### GranjaEstefania-PuntoVenta.cpp
Este programa en c++ permite obtener el valor de la compra de varios productos,contabilizando su valor con iva y realizando un descuento especial a la persona.

### GranjaEstefania-SumaN.cpp
Este programa en c++ tiene como finalidad que el usuario ingrese valores y le permita calcular la suma de numeros.

### GranjaEstefania-laedad.cpp
Este programa en c++ le permite calcular a una persona su edad ,meses y dias.

# Funcionalidad 

### GranjaEstefania-Compara.cpp
```
float JE_x,JE_y;
cout<<"Ingrese el valor de x: ";
cin>>JE_x;
cout<<"Ingrese el valor de y: ";
cin>>JE_y;
```
### GranjaEstefania-CuentaMoneda.cpp
```
int JE_n,JE_c=0,JE_c1=0,JE_c2=0,JE_c3=0;
float JE_x,JE_a=0,JE_a1=0,JE_a2=0,JE_a3=0;
cout<<"Cantidad de monedas a ingresar: ";
cin>>JE_n;
cout<<"Ingrese el valor de la moneda (0.10,0.25,0.50): ";
cin>>JE_x;
```
### GranjaEstefania-PuntoVenta.cpp
```
int JE_C=0,JE_P=0;
float JE_A=0,JE_x,JE_Tb,JE_PIVA,JE_Pdsc,JE_IVA=0,12,JE_dsc=0.25,JE_VT;
cout<<"Ingrese la cantidad de productos Comprados:  ";
cin>>JE_P;
cout<<"Ingrese el precio de productos:  $ ";
cin>>JE_x;
```
### GranjaEstefania-SumaN.cpp
```
int JE_C=0,JE_b;
float JE_S=0,JE_x;
cout<<"Ingrese la cantidad de numeros a sumar: ";
cin>>JE_b;
cout<<"Ingrese un numero: ";
cin>>JE_x;
```
### GranjaEstefania-laedad.cpp
```
int JE_dd,JE_mm,JE_yy,JE_dd1,JE_mm1,JE_yy1,JE_,da,JE_ma,JE_ya;
cout<<"Ingrese la Fecha Actual: Dia Mes Año";
cin>>JE_dd>>JE_mm,JE_yy;
cout<<"Ingrese la fecha de Nacimiento: Dia Mes Año" ;
cin>>JE_dd1>>JE_mm1>>JE_yy1;
```

# SALIDAS
### GranjaEstefania-Compara.cpp
```
cout<<"El valor de X: "<<JE_x<<"es igual a Y: "<<JE_y<<endl;
cout<<"El valor de X: "<<JE_X<<"es menor a Y: "<<JE_y<<endl;
cout<<"El valor de Y: "<<JE_y<<" es  menor a X: "<<JE_x<<endl;
```
### GranjaEstefania-CuentaMoneda.cpp
```
cout<<"Cantidad de monedas ingresadas: $ "<<JE_c<<endl<<endl;
cout<<"Canttidad total de dinero contado: $"<<JE_a<<endl<<endl;
cout<<"Cantidad de monedas de 0.10ctvs: "<<JE_c1<<endl;
cout<<"Cantidad de monedas de 0.10ctvs:$ "<<JE_a1<<endl<<endl;
cout<<"Cantidad de monedas de 0.25ctvs: "<<JE_c2<<endl;
cout<<"Cantidad de monedas de 0.25ctvs:$ "<<JE_a2<<endl<<endl;
cout<<"Cantidad de monedas de 0.50ctvs: "<<JE_c3<<endl<<endl;
cout<<"Cantidad de monedas de 0.50ctvs:$ "<<JE_a3<<endl;
```
### GranjaEstefania-PuntoVenta.cpp
```
cout<<"El valor del Iva de su compra es: $"<<JE_PIVA<<endl;
cout<<"El valor del Descuento de su compra es: $"JE_Pdsc<<endl;
cout<<"Elvalor total de su compra a pagar es: $" JE_VT<<endl;
```
### GranjaEstefania-SumaN.cpp
```
cout<<"La Suma total es: "JE_S<<endl;
```
### GranjaEstefania-laedad.cpp
```
cout<<"Usted tiene "<<JE_ya<<"años"JE_ma<<"meses"<<"y"<<JE_da<<"dias"<<endl;
```
# Instalacion

1.- Descargar F-Droid
```
https://f-droid.org/
```

2.- Descargar la terminal(Termux)
```
Dentro de la aplicacion F-Droid
```

3.-Instalar paquetes en la terminal(Termux)
```
=>pkg install git
=>pkg install vim
=>pkg install g++
=>pkg install clang
=>apt update
=>apt upgrade
```

4.-Clonar el Repositorio en la terminal
```
git clone https://github.com/Jeriko7/ACTIVIDAD-E2
```

5.- Acceder al Repositorio
```
cd ACTIVIDAD-E2
```
6.-Escribir Comandos ==> ls
```
GranjaEstefania-Compara
GranjaEstefania-Compara.cpp
GranjaEstefania-Compara.jpg
GranjaEstefania-SumaN
GranjaEstefania-SumaN.cpp
GranjaEstefania-SumaN.jpg
GranjaEstefania-laedad
GranjaEstefania-laedad.cpp
GranjaEstefania-laedad.jpg
GranjaEstefania-PuntoVenta
GranjaEstefania-PuntoVenta.cpp
GranjaEstefania-PuntoVenta.jpg
GranjaEstefania-CuentaMoneda
GranjaEstefania-CuentaMoneda.cpp
GranjaEstefania-CuentaMoneda.jpg
```
# Compilacion de un Programa

1.- Ingresar al Repositorio
```
cd ACTIVIDAD-E2
```
2.- Compilar Programa
```
g++ GranjaEstefania-Compara -o GranjaEstefania-Compara
```

# Ejecucion de un Programa
```
./GranjaEstefania-Compara
Presentacion del Programa.
```

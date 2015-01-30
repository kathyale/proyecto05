# proyecto
 #include<stdio>
#include<conio>
#include<stdlib>
#include<string>
#include<fstream>

int menu()
{
int op;

printf("         Menu : \n ");
    printf("     EJERCICIOS : \n ");
    printf("1.  Generar tablas de verdad con dos entradas \n ");
    printf("2.  Ver tablas de verdad con dos entradas \n ");
    printf("3.  Generar y ver tablas de verdadcon n entradas \n ");
    printf("4. Salir \n ");

     scanf("%d",& op);
return op;
}

//Creamos el archivo en funcion

bool existe()
     {
FILE *documento;
documento= fopen("C:/BC5/ARCHIVO/TABLAS.txt","rb");
if(documento!=NULL)
 {
  fclose(documento);
  return 1;
 }
else
 {
 fclose(documento);
 return 0;
 }
}




 void ejecutar(int op)
  {
   switch(op)
    {
      case 1:
      printf("  Generar tablas de verdad con dos entradas \n ");
      break;

     case 2:
     printf("  Ver tablas de verdad con dos entradas \n ");
     break;

     case 3:
     printf("  Generar y ver tablas de verdadcon n entradas \n ");
     break;

     case 4:
     printf(" Gracias :) ");
     break;
    }
  }




void main()
{
   int opc=0;
   while (opc!=4)
     {
		opc=menu();
		ejecutar(opc);
     }

}



trabajo final

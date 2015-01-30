# proyecto05
#include<stdio>
#include<conio>
#include<stdlib>
#include<string>

main()
{
 int a, b,op, base1, numero, v[20], p  ;
 do
 {
        printf("         Menu : \n ");
    printf("   EJERCICIOS : \n ");
    printf("1.  Generar tablas de verdad con dos entradas \n ");
    printf("2.  Ver tablas de verdad con dos entradas \n ");
    printf("3.  Generar y ver tablas de verdadcon n entradas \n ");
    printf("4. Salir \n ");

     printf("Elija una opcion:\n ");
     scanf("%d",& op);

        if (op >=1 & op <=3)
        {


    printf(" Ingrese el valor a trasformar");
    scanf("%d",& numero);
    printf(" \n ");

      }

     switch (op)
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

     default:
     printf("Opcion no valida \n ");
     break;
     }
     } while(op >=1 & op <4);

getch();
}


trabajo final

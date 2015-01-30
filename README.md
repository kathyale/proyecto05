#include<stdio>
#include<conio>
#include<stdlib>
#include<string>
#include<fstream>


main()
{
 int a, op   ;
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



     switch (op)
     {
     case 1:
     {

       printf("  Generar tablas de verdad con dos entradas \n ");
         ofstream archivo("C:/BC5/ARCHIVO/TABLAS.txt");
         printf(" Su archivo");
         {

        archivo<<" ta     ";

              	bool x;
   cout <<"x       *Not*   " << endl;

   cout<< true<<"         " <<!true<< endl;
   cout<<false<<"         "<<!false<<endl;
   cout<<endl;

   cout<<"xy        *And* "<< endl;

   cout<< false<<""<<false<<"   	  " <<(false&&false) << endl;
   cout<< false<<""<<true<<"   	  " <<(false&&true) << endl;
   cout<< true<<""<<false<<"   	  " <<(true&&false) << endl;
   cout<< true<<""<<true<<"    	  " <<(true&&true) << endl;
   cout<< endl;

	cout<<"xy        *Or* "<< endl;
   cout<< false<<""<<false<<"  	  " <<(false||false) << endl;
   cout<< false<<""<<true<<"  	  " <<(false||true) << endl;
   cout<< true<<""<<false<<"  	  " <<(true||false) << endl;
   cout<< true<<""<<true<<"  	  " <<(true||true) << endl;
   cout<< endl;

   cout<<"xy 	  *No-And*"<< endl;
   cout<< false<<""<<false<<"  	   "; cout<<"1" << endl;
   cout<< false<<""<<true<<"   	   " ;cout<<"1"<< endl;
   cout<< true<<""<<false<<"   	   " ;cout<<"1"<< endl;
   cout<< true<<""<<true<<"   	   "; cout<<"0"<< endl;
     cout<< endl;

   cout<<"xy	    *No-Or* "<< endl;
   cout<< false<<""<<false<<"  	   "; cout<<"1" << endl;
   cout<< false<<""<<true<<"   	   " ;cout<<"0"<< endl;
   cout<< true<<""<<false<<"   	   " ;cout<<"0"<< endl;
   cout<< true<<""<<true<<"   	   "; cout<<"0"<< endl;
   cout<< endl;

   cout<<"xy 	   *X-Or* "<< endl;
   cout<< false<<""<<false<<"  	   "; cout<<"0" << endl;
   cout<< false<<""<<true<<"   	   " ;cout<<"1"<< endl;
   cout<< true<<""<<false<<"   	   " ;cout<<"1"<< endl;
   cout<< true<<""<<true<<"   	   "; cout<<"0"<< endl;
   cout<< endl;

   cout<<"xy 	  *X-Nor* "<< endl;
   cout<< false<<""<<false<<"  	   "; cout<<"1" << endl;
   cout<< false<<""<<true<<"   	   " ;cout<<"0"<< endl;
   cout<< true<<""<<false<<"   	   " ;cout<<"0"<< endl;
   cout<< true<<""<<true<<"   	   "; cout<<"1"<< endl;
   cout<< endl;

                   }
           archivo.close();



      break;
      }


     case 2:
     {
     printf("  Ver tablas de verdad con dos entradas \n ");

     break;
     }

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
     } while(op >=1 & op <=4);

getch();
}


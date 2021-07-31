Línguagem C

# calculadora

//Calculadoras basicas

#include<stdio.h>
INT main()
{
//Calculadora de área e volume de cubos e retângulos

int largura,altura, volume, AB, AL,Atotal, comprimento;

    printf("Digite a altura:\n");
    scanf("%i", &altura);

    printf("Digite a largura:\n");
    scanf("%i", &largura);
    
    printf("Digite o comprimento:\n");
    scanf("%i", &comprimento);
    
    AB= comprimento*largura;
    printf("\n A Área da base é: %i\n", AB);
    
    AL= comprimento*altura;
    printf("\n A área de um lado é:%i\n",AL);
    
    Atotal= (2*AB) +( 4* AL);
    printf("\n A área total é: %i\n", Atotal);
  
    volume= largura *altura * comprimento;

    printf("\n O volume total é: %i\n",volume);

return 0;
}

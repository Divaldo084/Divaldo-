#include <stdio.h>

    int main(){


        printf("carta 1:\n");

        char estado;
        char codigo[50];
        char nome_da_cidade;
        int população;
        float area;
        float pib;
        int numero_de_pontos_turisticos;
        float densidade_populacional;
        float PIB_per_capita;
        float super_poder;



        printf("Digite o nome do estado:(ex: A a H)\n");
        scanf("%s", &estado);

        printf("Digite o código do estado:(EX: a01, b03)\n");
        scanf("%s", &codigo);

        printf("Digite o nome da cidade:\n");
        scanf("%s", &nome_da_cidade);

        printf("Digite a população:\n");
        scanf("%d", &população);

        printf("digite a area:\n");
        scanf("%f", &area);

        printf("digite o pib:\n");
        scanf("%f", &pib);

        printf("digite o numero de pontos turisticos:\n");
        scanf("%d", &numero_de_pontos_turisticos);

        printf("digite a densidade populacional:\n");
        scanf("%f", &densidade_populacional);

        printf("digite o pib per capita:\n");
        scanf("%f", &PIB_per_capita);
        
               printf("a densinade populacional da carta 1 é é: %.2f \n", população / area);
               printf("o pib percapita da carta 1 é: %f \n", pib / população);
               printf("o super poder da carta 1 é: %f \n", (densidade_populacional + pib + população + area + PIB_per_capita) / 2);



        printf("carta 2:\n");

              
        printf("Digite o nome do estado:(ex: A a H)\n");
        scanf("%s", &estado);

        printf("Digite o código do estado:(EX: a01, b03)\n");
        scanf("%s", &codigo);

        printf("Digite o nome da cidade:\n");
        scanf("%s", &nome_da_cidade);   

        printf("Digite a população:\n");
        scanf("%d", &população);

        printf("digite a area:\n");
        scanf("%f", &area);

        printf("digite o pib:\n");
        scanf("%f", &pib);

        printf("digite o numero de pontos turisticos:\n");
        scanf("%d", &numero_de_pontos_turisticos);

        printf("digite a densidade populacional:\n");
        scanf("%f", &densidade_populacional);

        printf("digite o pib per capita:\n");
        scanf("%f", &PIB_per_capita);

        printf("a densinade populacional da carta 2 é é: %f \n", população / area);
        printf("o pib percapita da carta 2 é: %f \n", pib / população);
        

        printf("o super poder da carta 2 é: %f \n", (densidade_populacional + pib + população + area + PIB_per_capita) / 2);

        return 0;
    }

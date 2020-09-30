#include <stdio.h>
#include <stdlib.h> 
#include <time.h> 


void zarAt(){
	printf("          Random zar atma uygulamsina hosgeldiniz\n");
	printf("          -------------------------------------------\n");
	printf("          Zarlari atmak icin herhangi bir tusa basin\n\n");
	getch();
	
	int sayac=0;
	int zar;
	srand(time(NULL));
	
	for(;sayac<3;sayac++){
		if(sayac == 0){
			printf("          zarlar sirasiyla ");
	
		}
		if(sayac == 1){
			zar = (rand() % 7);
			printf("%d ve ",zar);
	
		}
		if(sayac == 2){
			zar = (rand() % 7);
			printf("%d dir." ,zar);
	
		}
	}

	getch("          cikmak icin herhangi bir tusa basin");

}

void lisans(){
	
	printf("\n\n          -----------------------\n");
	printf("           MADE BY HALIL ACIKGOZ\n");
	printf("          -----------------------");
	getch();
}


int main(){
	
	
	zarAt();
	lisans();
	
	return 0;
}

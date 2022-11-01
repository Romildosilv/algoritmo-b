algoritmo-b
Impa par//

int num, resto;
int main(){
printf("Digite um numero\n");
scanf("%d", &num);
resto=num%2; //divisao por dois
if(resto==0){
	printf("\nSeu numero e par\n");

}
else{
	printf("\nSeu numero e impar\n");
}
	

return 0;
}

Alternativa//

int num;
int main(){
printf("Digite um numero\n");
scanf("%d", &num);
if(num%2==0){
	printf("\nSeu numero e par\n");

}
else{
	printf("\nSeu numero e impar\n");
}
	

return 0;

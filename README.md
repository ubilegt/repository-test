#include <stdio.h>
#include <conio.h>
int main() {
	int i,n,a[100];
	int max;
	printf("array n= ");
	scanf("%d" , &n);
	for(i=0;i<n;i++){
		printf("enter array[%d]=" , i);
		scanf("%d" , &a[i]);
	}
	
	max = a[0];
	
	for(i=0;i<n;i++){
		if(max < a[i]){
			max = a[i];
		}
	}
	
	printf("max = %d" , max);
	getch();
	return 0; 
}


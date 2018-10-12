#include<stdio.h>
#include<conio.h>

int main () {
	
	while(1) {
	
	
	double grade1,grade2;
	double average;
	
	printf("Enter the your first grade1: ");
	scanf("%lf",&grade1);
	
	
	printf("Enter the your second grade2: ");
	scanf("%lf",&grade2);

	
	average=((grade1*40)/100)+((grade2*60)/100);
	
	printf("Sonuc=%lf\n",average);
	
	if(average>=90)
	{
		printf("Sonuc= AA\n");
	}
	
	if(average<90 && average>=85)
	{
		printf("Sonuc= BA\n");
	}	
	
	if(average<85 && average>=80)
	{
		printf("Sonuc= BB\n");	
	}
	
	if(average<80 && average>=75)
	{
		printf("Sonuc= CB\n");	
	}
	
	if(average<75 && average>=65)
	{
		printf("Sonuc= CC\n");
	}
	
	if(average<65 && average>=58)
	{
		printf("Sonuc= DC\n");
	}
	
	if(average<58 && average>=50)
	{
		printf("Sonuc= DD\n");
	}
	
	if(average<50 && average>=40)
	{
		printf("Sonuc= FD\n");
	}
	
	if(average<40)
	{
		printf("Sonuc= FF\tsalaksinki\n");
		
	}
	


	
	
	
	
	
	
}
	
	getch();
	
	return 0;
}

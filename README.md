# baitapC2
//bai tap tinh tien dien
#include<stdio.h>
#include<conio.h>
#include<math.h>
main(){
	float csc,csm,sth,tiendien ;
	printf("nhap chi so cu : ");
	scanf("%f",&csc);
	printf("Nhap chi so moi : ");
	scanf("%f",&csm);
	if (csc<csm) {
	
	sth=csm-csc;}
	if (sth<50)
	   { tiendien=1500*sth;
	   printf(" So tien dien phai tra la %f : ",tiendien);
	   }
	else if(sth>=50 and sth<150)
	{ tiendien=2000*(sth-50)+50*1500;
	printf("Tien dien phai tra la %f : ",tiendien);}
	      else {
	      	tiendien=50*1500+100*2000+(sth-150)*2500;
	      	printf("Tien dien phai tra la %f : ",tiendien);
		  }
	}

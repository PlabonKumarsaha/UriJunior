#include<stdio.h>

int main(){

     float N;
    int a,b,c,d,e,f,g,m,n,h,i,j,k,l;
int x,y;
    scanf("%f", &N);
    m=(int)N;
    a=m/100;
    m%=100;
    b=m/50;
    m%=50;
    c=m/20;
    m%=20;
    d=m/10;
    m%=10;
    e=m/5;
    m%=5;
    f=m/2;
   g= m%2;

printf("N= ==%d\n",N);

    x=N*100;
    printf("x-i ==%d\n",x);
    n=(int)x;
printf("n-x ==%d\n",n);

    n=n%100;
    printf("n-100 ==%d\n",n);
    h=n/50;
    n=n%50;
    printf("n-50 ==%d\n",n);
    i=n/25;
    n%=25;
    printf("n-i ==%d\n",n);
    j=n/10;
    n%=10;
    printf("n-k ==%d\n",n);
    k=n/5;
    printf("n-l ==%d\n",n);
        l=n%5;


    printf ("NOTAS:\n");
    printf ("%d nota(s) de R$ 100.00\n",a);
    printf ("%d nota(s) de R$ 50.00\n",b);
    printf ("%d nota(s) de R$ 20.00\n",c);
    printf ("%d nota(s) de R$ 10.00\n",d);
    printf ("%d nota(s) de R$ 5.00\n",e);
    printf ("%d nota(s) de R$ 2.00\n",f);
    printf ("MOEDAS:\n");
    printf ("%d moeda(s) de R$ 1.00\n",g);
    printf ("%d moeda(s) de R$ 0.50\n",h);
    printf ("%d moeda(s) de R$ 0.25\n",i);
    printf ("%d moeda(s) de R$ 0.10\n",j);
    printf ("%d moeda(s) de R$ 0.05\n",k);
    printf ("%d moeda(s) de R$ 0.01\n",l);



    return 0;
}

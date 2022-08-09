/*# addition-of-matrices*/
#include stdio.h>
#include<conio.h>
int main()
{
int r,c,a[100][100],b[100][100],sum[100][100],i,j;
printf("enter the rows:-/n");
scanf("%d", &r);
printf("enter the columns:-/n");
scanf("%d", &c);
printf("/n enter the values of first matrix:- /n ");
scanf("%d" ,&a");
for(i=0;i<r;++i)
for(j=0;j<c;++j)
printf("enter the a :%d,%d" , i+1,j+1 );
scanf("d", &a[i][j]);
}
{
printf("/n enter the values of second matrix:- /n");
scanf("%d",&b);
for(i=0;i<r;++i)
for(j=0;j<c;++j)
printf("enter the b :%d,%d" , i+1,j+1 );
scanf("d", &b[i][j]);
}
{
*/sum of two matrix*/
for (i=0;i<r;++i)
for(j=0;j<c;++j)
sum[i][j]=a[i][j]+b[i][j];
}
{
//printing the matrices
printf("/n result= /n");
for(i=0;i<r;++i)
for(j=0;j<c;++j)
printf("%d",sum[i][j]);
}
return 0;


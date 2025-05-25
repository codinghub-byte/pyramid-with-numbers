# pyramid-with-numbers
#include <stdio.h>
void main()
{
int n, i, j, s;
printf("Enter number of rows : ");
scanf("%d", &n);
// Fill the missing code
for(i=1;i<=n;i++)
{
for(j=i;j<n;j++)
{
printf(" ");
}
for(s=1;s<=i;s++)
{
printf("%d ",s);
}
printf("\n");
}
}

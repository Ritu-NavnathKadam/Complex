# Complex
#include <stdio.h>
void main()
 {
    int n,r1,r2,i1,i2,add_of_complex,real,img,res,res2;
    printf("Enter first real part  ");
    scanf("%d",&r1);
    printf("Enter first imaginary part  ");
    scanf("%d",&i1);
    printf("Enter second real part  ");
    scanf("%d",&r2);
    printf("Enter second imaginary  part  ");
    scanf("%d",&i2);
    
    do
    {
    printf("1.Add\n");
    printf("2.sub\n");
    printf("3.mul\n");
    printf("4.exit\n");
    printf("Enter your choice\n");
    
    scanf("%d",&n);
    
    switch(n)
    {
    case 1:
    real=r1+r2;
    img=i1+i2;
    printf("Addition = %d+%di\n",real,img);
    printf("\n");
    break;
    
    case 2:
    real=r1-r2;
    img=i1-i2;
    printf("substraction =(%d-%di)\n",real,img);
    printf("\n");
    break;
    
    case 3:
    res= r1*r2-i1*i2;
    res2=r1*i2+i1*r2;
    printf("Multiplication = %d + %di\n",res,res2);
    printf("\n");
    break;
    }
    }
    while(n!=4);
    
    
}

//# c-12
//sum of odd numbers
#include <stdio.h>
int main()
{
    int i,n,sum=0;
    printf("enter the number:");
    scanf("%d",&n);
    for(i=1;i<=n;i++)
    {
        if(i%2!=0)
        {
            sum+=i;
        }
    }    
            printf("sum of odd numbers:%d",sum);
        return 0;
}

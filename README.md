# Print-divisor-of-any-number-less-time-complexity.
#include <stdio.h>
#include<math.h>

int main()
{   int n,i;
    printf("Enter a number:");
    scanf("%d",&n);
    
    for(i=1;i*i<n;i++)
    {
        if(n%i==0)
          printf("%d ",i);
    }
   for( i=i;i>=1;i--)
   {
       if(n%i==0)
          printf("%d ",n/i);
   }
    return 0;
}

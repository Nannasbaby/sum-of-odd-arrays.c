#include <stdio.h>
int main()
{
    int arr[9],sum=0;
    for(int i=1;i<9;i++)
    scanf("%d",&arr[i]);
    
    for(int i=0;i<9;i++)
    printf("%d\t",arr[i]);
    printf("\n");
    
    for(int i=0;i<9;i++)
    if(arr[i]%2==1)
    {
        sum=sum+arr[i];
        
    }
    printf("%d",sum);
}

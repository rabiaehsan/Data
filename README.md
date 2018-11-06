#include<stdio.h>
#include<conio.h>
int binarySearch(int arr[],int num,int size)
{
int low,high,mid;
low=0;
high size-1;
while(low<=high)
{
mid=(low+high)/2;
}
if(arr[mid]==num)
{
return mid+1;
}
else if(arr[mid]>num)
{
high =mid-1;
}
else if(arr[mid]<num)
{
low =mid +1;
} return -1;
}int main(void)
{
int arr[8]={1,2,3,4,5,6,7,8};
len,num,result;
int target;
printf("\nvalues in array :\t");
for(len=0;len<=7;len++)lc
{
printf("%d\t",arr[len]);
}printf("\n enter the element to search \t");
scanf("%d",&target);
result=bainrySearch(arr,target,8);
if(result>=8)
printf("\n %d found at loation %d",target,result);
}
else{
printf("\n %d not found in array ",target);
}
getch();
}


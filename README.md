# find-sum-of-digit-in-c-language
 # include<stdio.h>
int getSum(int n)
{
   int sum =0;
   while (n != 0)
   {
       sum = sum + n%10;
       n = n/10;
   }
   return sum;
}

int main()
{
  int n ;
  printf("enter the number:");
  scanf("\n%d",&n);
  printf("%d ", getSum(n));
  return 0;
}

# choose-between
这是一个比较三个数大小的小程序
#include<stdio.h>
int main()
{int a,b,c;
  printf("please intput three number");
  scanf("%d,%d,%d\n",&a,&b,&c);
  if(a>=b)
   {if(c>=a)
      printf("%d,%d,%d\n",c,a,b);
    else if(c>=b)
            printf("%d,%d,%d\n",a,c,b);
         else
            printf("%d,%d,%d\n",a,b,c);
    }
   else
      {if (c<=a)
         printf("%d,%d,%d\n",b,a,c);
       else if(c<=b)
               printf("%d,%d,%d\n",b,c,a);
              else
               printf("%d,%d,%d\n",c,b,a);
       }
   return 0;
 }

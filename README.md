# swap-two-number-without-third-variable
#swap two number without using third variable like temp use only logic
#include <stdio.h>
#swap two number without using third variable
int main() {
   int x,y;
   printf("\n enter valueof x and y:");
   scanf("%d%d",&x,&y);
   printf("Before swapping x=%d and y=%d\n",x,y);
  x=x+y;
  y=x-y;
  x=x-y;
    printf("After swapping x=%d and y=%d\n",x,y);
   
}
/*OUTPUT:
enter valueof x and y:12
23
Before swapping x=12 and y=23
After swapping x=23 and y=12
*/

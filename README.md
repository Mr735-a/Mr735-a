#include<stdio.h>

int main(){
    int mark;
    printf(" mark");
    scanf("%d\n",mark);
    
      if (mark>30){
        printf("C Grade\n");
    }
      else if (mark>30 && 70<=mark){
       printf("B Grade\n");
    }
    else if (mark>70 && 90<=mark){
        printf("A Grade\n");
   }
    else if (mark>90 &&100 <=mark){
        printf("A+ Grade\n");
   }
    else {
        printf("not mark\n");
    }
    return 0;
        
}

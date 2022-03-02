#include <stdio.h>

int main() {
    int i,j;
    for(i=1;i<=6;i++){ //here we are taking for row lines
        for(j=1;j<=i;j++){ //here we are taking for colomn lines
            printf("*");
        }
    printf("\n");
    }
    return 0;
}

2.#include <stdio.h>

int main() {
  int i,j;
  for(i=1;i<=6;i++){     //incrementing the stars
      for(j=6;j>=i;j--){   //decrementing the stars(columns)
          printf("*");
          
        
      }
printf("\n");
  }
    return 0;
}

3.#include <stdio.h>

int main() {
  int i,j,k;
  for(i=1;i<=6;i++){
      for(j=i;j<6;j++){
          printf(" ");
      }
          for(k=1;k<=i;k++){
              printf("*");
              
          }
     
      
       printf("\n");
  }
    return 0;
}

4.#include <stdio.h>

int main() {
  int i,j;
  for(i=0;i<=5;i++){
      for(j=0;j<5;j++){
          if(j>=5-i){
              printf("*");
          }
              else{
                  printf(" ");
              }
          
      }
printf("\n");
  }
  
    return 0;
}

5.int main() {
  int i,j;
  for(i=1;i<=5;i++){
      for(j=1;j<=9;j++){
          if(j>=6-i&&j<=4+i){
              printf("*");
          }
              else{
                  printf(" ");
              }
          
      }
printf("\n");
  }
  
    return 0;
}

6.
#include<stdio.h>

int main() {
  int i,j;
  for(i=1;i<=4;i++){
      for(j=1;j<=7;j++){
          if(j>=0+i&&j<=8-i){   // looping with the if condition
              printf("*");
          }
              else{
                  printf(" ");
              }
          
      }
printf("\n");
  }
  
    return 0;
}

7.#include<stdio.h>

int main() {
  int i,j;
  for(i=1;i<=6;i++){
      for(j=1;j<=6;j++){
          printf(" * ");
      }
      printf("\n");
  }
          
  
    return 0;
}


9.int main()  
{  
    int n;  
    printf("Enter the number of rows");  
    scanf("%d",&n);  
    for(int i=n;i>=1;i--)  
    {  
        for(int j=1;j<=i-1;j++)  
        {  
            printf(" ");  
        }  
        for(int k=1;k<=n;k++)  
        {  
           if(i==1 || i==n || k==1 || k==n)  
            printf("*");  
            else  
            printf(" ");   
        }  
        printf("\n");  
    }  
    return 0;  
}


10.int main()  
{  
    int n;  
    printf("Enter the number of rows");  
    scanf("%d",&n);  
    for(int i=1;i<=n;i++)  
    {  
        for(int j=1;j<i;j++)  
        {  
            printf(" ");  
        }  
        for(int k=1;k<=n;k++)  
        {  
           printf("*");  
              
        }  
        printf("\n");  
    }  
    return 0;  
}

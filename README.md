# Programs
Codes
1.//ASCII Value of character:
#include<stdio.h>
int main() {
    char ch;
    printf("enter character:");
    scanf("%c",&ch);
    int x = ch;
    printf("char val is %d",x);
}
2.//celsius to fahrenheit
#include<stdio.h>
int main() {
    float fah,c;
    printf("enter vals:");
    scanf("%f",&c);
    fah = (1.8 * c) + 32;
    printf("the converted val is %f",fah);
    
}
3.//swap two variables
#include<stdio.h>
int main() {
    int a,b;
    printf("enter two values:");
    scanf("%d %d",&a,&b);
    int temp;
    temp = a;
    a = b;
    b = temp;
    printf("The swap values is %d %d",a,b);
}
4.//given num is even or odd
#include<stdio.h>
int main() {
    int n;
    printf("enter the val:");
    scanf("%d",&n);
    if(n%2==0){
        printf("even");
    }else{
        printf("odd");
    }
}

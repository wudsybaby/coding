# coding

#include <stdio.h>
double perimeter(double x);
double area(double w);
int main (){
    double x, w;
    printf("Enter the length: ");
    scanf("%lf", &x);
    prntf("Enter the width: ");
    scanf("%lf", &w)
    printf("The perimeter is %lf\n", perimeter);
    printf("The area is %lf\n", area);
    return 0;   
}   
double perimeter(double x, w){
    return (2*x)+(2*w);
}
double area(double x, w){
    return (x*w);
}

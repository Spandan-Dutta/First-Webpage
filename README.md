# First-Webpage
This webpage is built using hmtl and internal css, about gym form. In mage has been added in the background. 
Any one who want to learn to create a single static webpage can take this as a reference
#include <stdio.h>
  int main() {
    int a[10];
    int i;
    int greatest;
    printf("Enter ten values:");
    //Store 10 numbers in an array
    for (i = 0; i < 10; i++) {
    scanf("%d", &a[i]);
    }
    //Assume that a[0] is greatest
    greatest = a[0];
    for (i = 0; i < 10; i++) {
if (a[i] > greatest) {
greatest = a[i];
    }
    }
    printf("
    Greatest of ten numbers is %d", greatest);
    return 0;
  }

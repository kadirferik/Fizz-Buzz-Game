# Fizz-Buzz-Game
```C
#include <stdio.h>
#include <stdlib.h>

int main(int argc, const char * argv[]) {
    int a,sayac = 0;
    printf("Bir sayi giriniz\t");
    scanf("%d",&a);
    while (sayac <= a){
        sayac += 1;
        if(sayac % 3 == 0 && sayac % 5 == 0){
            printf("FizzBuzz\n");
        }
        else if (sayac % 3 == 0){
            printf("Fizz\n");
        }
        else if (sayac % 5 == 0){
            printf("Buzz\n");
        }
        else{
            printf("%d\n", sayac);
        }
    }
    
    return 0;
}
```

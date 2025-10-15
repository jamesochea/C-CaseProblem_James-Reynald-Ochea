#include <stdio.h>

int main() {
    
    printf("Name: James Reynald Ochea\n");
    printf("ID Number: 2025304159\n\n");

    
    float celsius, fahrenheit;

    
    printf("Enter temperature in Celsius: ");
    scanf("%f", &celsius);

    
    fahrenheit = (celsius * 9 / 5) + 32;

    
    printf("Temperature in Fahrenheit: %.2f°F\n", fahrenheit);

    return 0;
}

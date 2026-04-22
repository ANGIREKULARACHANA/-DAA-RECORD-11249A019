#include <stdio.h>
int fibonacci(int n) {
if (n == 0) {
return 0;
} else if (n == 1) {
return 1;
}
else {
return (fibonacci(n - 1) + fibonacci(n - 2));
}
}
int main() {
int num_terms, i;
printf("Enter the number of terms for the Fibonacci series: ");
scanf("%d", &num_terms);
if (num_terms < 0) {
printf("Fibonacci series is not defined for negative terms.\n");
} else {
printf("Fibonacci Series up to %d terms:\n", num_terms);
for (i = 0; i < num_terms; i++) {
printf("%d ", fibonacci(i));
}
printf("\n");
}
return 0;
}

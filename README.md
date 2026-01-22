#include <stdio.h>

int main() {
    int n, i;
    float marks, sum = 0, average;

    printf("Enter number of subjects: ");
    scanf("%d", &n);

    for(i = 1; i <= n; i++) {
        printf("Enter marks for subject %d: ", i);
        scanf("%f", &marks);
        sum += marks;
    }

    average = sum / n;
    printf("Average Marks = %.2f\n", average);
    return 0;
}
# marksresult
Enter Principal amount: 5000


Enter Rate of interest: 5

Enter Time (in years): 2

Практична робота №1 Мануйленко Микола

#include <stdio.h>

int main() {
    double time1, time2, time3;
    
    scanf("%lf %lf %lf", &time1, &time2, &time3);
    
    double speed1 = 1 / time1;
    double speed2 = 1 / time2;
    double speed3 = 1 / time3;
  
    double combined_speed = speed1 + speed2 + speed3;
    
    double total_duration = 1 / combined_speed;
    
    printf("%.2f\n", total_duration);
    
    return 0;
}

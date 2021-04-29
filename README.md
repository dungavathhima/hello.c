#include<stdio.h>
#include<stdlib.h>
int main();
typedef struct(){
 char employee_name[30];
 int employee_number;
 int employee_salary;
 int service_year;
 } employee
 int main(){
int i,n=20;
employee employees[n];
printf("Enter %d employee details \n \n",n);
for(i=0;i<=20;i++){
 printf("Employee:%d \n ",i+1);
 printf("name:");
scanf("%s", &employees[i]. employee_name);
printf("ID:");
scanf("%d", &employee[i].employee_number);
printf("salary:");
scanf("%d",&employee[i].salary);
printf("year of service:");
scanf("%d"& employee[i].service_year);
}
printf("-----------all the employee details-----------\n");
for(i=0;i<=n;i++);
printf("employee name\t:");
printf("%s\n", employee[i].employee _name);
printf("employee number\t:);
printf("%d\n", employee[i].employee_number);
printf("salary\t");
printf("%d\n", employee[i].salary);
printf("year of service\t");
printf("%d\n",employee[i].service_year);
printf("\n");
}
return 0;
}

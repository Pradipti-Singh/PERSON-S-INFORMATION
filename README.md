# PERSON-S-INFORMATION
In this , a person has to enter a few informations
#include<stdio.h>
struct address
{
char city[20]; 
int pin;
char phone[14];
};
struct employee
{
char name[20]; 
struct address add;
};
void main ()
{
struct employee emp;
printf("Enter employee information?\n 1. NAME\n 2. CITY\n 3. PINCODE \n 4. PHONE");
scanf("%s %s %d %s",emp.name,emp.add.city, &emp.add.pin, emp.add.phone); 
printf("Printing the employee information. ..\n");
printf("name: %s\nCity: %s\nPincode: %d\nPhone: %s",emp.name,emp.add.city,emp.add. 
pin,emp.add.phone);
}

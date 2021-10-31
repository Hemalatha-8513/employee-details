# employee-details
a program to print employe details such as id ,number, salary etc.....
#include<stdio.h>
#include<stdlib.h>
  tpyedef struct{
     char name[30];
     int id;
     double basic_salary;
     double net_salary;
 }employee;
     int main()
     {
     	//number of employees
     	int n=2
     	//array to store structure values of all employes
     	employee employees[n];
     	//taking each employee detail as input
     	printf("enter %d employee details \n\n",n);
     	for(int i=0;i<n;i++){
     		printf("employee %id:-\n",(i+1));
     		//name
     		printf("name:");
     		scanf("%[\n]s",employees[i],name);
     		//ID
     		printf("ID:");
     		scanf("%d[\n]s",employees[i].id);
     		//salary
     		printf("%1f",&employees[i].basic_salary);
     		//to consume extra '\n' input
     		char ch=getchar();
     		empolyees[i].net_salary=employees[i].basic salary*1.03;
		 }
		 //displaying employee details
		 print(".....all employees details....\n");
		 for(int i=0;i<n;i++){
		 	printf("name\t:");
		 	printf("\n",employees[i].name);
		 	printf("id \t:");
		 	printf("2.1f\n;employees[i].net_salary");
		 	printf("\n");
		 }
		 return 0;
	 }

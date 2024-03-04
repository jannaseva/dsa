#include<stdio.h>
int i,n;
struct EMP
{
	char emp_name[20];
	int emp_no,basic;
	float gross,net_salary,all_allowances,IT;
}e[5];
void readdata()
{
	printf("\nenter how many emps?:");
	scanf("%d",&n);
	for(i=0;i<n;i++){
	printf("\nEnter the Emp_Name\t Emp_Num \t Bassci_sal of %d:",i);
	scanf("%s%d%d",e[i].emp_name,&e[i].emp_no,&e[i].basic);
}
}
void calculate()
{
	for(i=0;i<n;i++)
	{
		e[i].all_allowances=1.23*e[i].basic;
		e[i].gross=e[i].basic+e[i].all_allowances;
		e[i].IT=0.3*e[i].gross;
		e[i].net_salary=e[i].gross-e[i].IT;
		
	}
}
void displaydata()
{
	printf("\t\t\t\t\tEmployee Details");
	printf("\nEmployee_Name\tEmployee_Number\tBasic_Salary\tGross_Salary\tNet_Salary\tAll_Allowances\t\tIT");
	for(i=0;i<n;i++)
printf("\n%-15s\t%-15d\t%-15d\t%-15.2f\t%-15.2f\t%-18.2f\t%-18.2f\n",e[i].emp_name,e[i].emp_no,e[i].basic,e[i].gross,e[i].net_salary,e[i].all_allowances,e[i].IT);
}
int main()
{
	readdata();
	calculate();
	displaydata();
	return 0;
}

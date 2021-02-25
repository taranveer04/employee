# employee
 #include<stdio.h>


       struct Employee
       {
              int number;
              char Name[25];
              int Age;
              long Salary;
       };

       void main()
       {

              struct Employee E;             


                    printf("\nEnter Employee Name : ");
                    scanf("%s",&E.Name);

                    printf("\nEnter Employee Age : ");
                    scanf("%d",&E.Age);
                    printf("\nEnter Employee number : ");
                    scanf("%d",&E.number);


                    printf("\nEnter Employee Salary : ");
                    scanf("%ld",&E.Salary);

                
                    printf("\nEmployee Name : %s",E.Name);
                    printf("\nEmployee Age : %d",E.Age);
                    printf("\nEmployee number : %d",E.number);
                    printf("\nEmployee Salary : %ld",E.Salary);


       }

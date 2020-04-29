# Apache-Spark

### Apache Spark - Dataframe 

##### Downlaods Dataset :
	1. department_dataset
	2. employee_bonus
	3. employee_dataset
	
#####Downlaods jar files:
	1. commons-csv-1.5
	2. spark-csv_2.10-1.5.0
	
#####Start Spark :

    spark-shell --master yarn --jars commons-csv-1.5.jar,spark-csv_2.10-1.5.0.jar


####Answer following questions:

1. Create a relation with employee dataset with schema (column
names and datatype) and name it employee. Once created, describe
the relation.

2. Select the columns from the employee relation. Display 10 of these
records on your screen.
3. Create a relation with department dataset with schema (column
names and datatype) and name it departments. Once created,
describe the relation.
4. Select the columns from the department relation. Display 10 of
these records on your screen.
prog8450: big data solution architecture 2
5. Create a relation with bonus dataset with schema (column names
and datatype) and name it bonus. Once created, describe the relation.
6. Select the columns from the bonus relation. Display 10 of these
records on your screen.
7. Join employee and department dataset to display Department
Name and Department Address (as 3 separate columns - street,
city and state) for each row in employee. Display 10 of these
records on your screen.
8. Display all the employees who received bonus. The result should
not display any employees who did not receive a bonus. Display
10 of these records on your screen.
9. Display the average bonus by department.
10. Display the number of employees in each department.

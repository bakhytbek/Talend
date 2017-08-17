Homework task:
1. Basing on source files, create data model for employees and offices(FK from 'Employee' to 'Office', new auto increment employee_id)
2. load data from 3 diff sources( 2 for employees + 1 of offices) into mdm, get rid of duplicated employees(consider one of the file primary, first name + last name is unique identifier for employee)
3. create default view to display joined entities( display employee and office info simultaneously) (web filter on UI)
3. create a trigger before adding new row  - check that number of employee of this office not greater then 50, if greater - display the message on webUI
4. create a process to load employee and offices entities to any desired database from MDM Server, to be called manually from web interface - the process should call a job.
5. create a smartview process: customize displaying of employee attributes and display on google maps city location of the employee

Output:
exported container, model, view, trigger, process(MDM->database load), smartview process,
job for files->MDM load, job for MDM->database load.

Please use best practices for jobs creation(context, prejobs-postjobs etc.) and create them in the way like you are going to deploy them on production system.

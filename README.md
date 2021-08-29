# HIVE-Project
# FUTURE 4 IT

### DESCRIPTION
->This project created in hive. <br> 
->This project is aboout create and maintain a database for candidate enrollment where they provide training for various courses. <br>
->In this project we created five tables. <br>
->We performed various operations in this project like table join, partitioning, updating etc. <br>
->We also performed queries in tables where we extracted the data from it. <br>
->We run this project in hive terminal in cdh5 and hue from browser. <br>

### TOOLS AND TECHNOLOGIES

1)Cloudera5 
2)Hadoop 
3)Hue 
4)Github 
5)Microsoft Excel 
6)Microsoft Powerpoint 
->This project created in hive.  ->This project is aboout create and maintain a database for candidate enrollment where they provide training for various courses.  ->In this project we created five tables.  ->We performed various operations in this project like table join, partitioning, updating etc.  ->We also performed queries in tables where we extracted the data from it.  ->We run this project in hive terminal in cdh5 and hue from browser. 

### FEATURES

->Availability of multiple courses, Discounts on each course. 
->Availability of demo sessions on weekdays as well as weekends. 
->Rescheduling of demo session if missed. 
->Multiple payment modes. 
->Installments availability on any types of payment mode. 
->Availability of both Online and Offline mode of training. 
->Updation can be performed on master table. 

### TABLES

1)ENQUIRY table(ORC and master table) 
2)DEMO_SCHEDULE table 
3)DEMO_MISSED table 
4)COURSE_ENROLL Table 
5)BATCH_DISTRIBUTION table 

### enquiry table(ORC and master table)

Created student table having attributes ID,NameMail. Mobile_no, Course, Fee, Discount, Date Status,status_final

Demo_Schedule table

It is taken from student table who has done their demo with added attributes like demoday (WD,WE),day,time

###  demo_missed table

Data for this table taken from student table whose status is DND and adding attributes like string,reschedule_datetime

### enroll table

This table contains list of all the students who have enrolled and drop course.data taken from demo done table with some added attributes like payment_mode,total_installment,installment_paid,next_installment_date,payment_date,payment_status,installment_left,final_fee

### batch table

this table contains details of students who joined training where data is taken from enroll table with added attributes like joining_date,week_day,day,time

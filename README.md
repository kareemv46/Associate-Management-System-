# HIVE PROJECT
# Associate-Management-System

### DESCRIPTION
* This project created in hive. <br> 
* This project is aboout create and maintain a database for candidate enrollment where they provide training for various courses. <br>
* In this project we created five tables. <br>
* We performed various operations in this project like table join, partitioning, updating etc. <br>
* We also performed queries in tables where we extracted the data from it. <br>
* We run this project in hive terminal in cdh5 and hue from browser. <br>

### TECHNOLOGIES USED
1)Cloudera5 <br>
2)Hadoop <br>
3)Hue <br>
4)Github <br>
5)Microsoft Excel <br>
6)Microsoft Powerpoint <br>

### FEATURES
* Availability of multiple courses, Discounts on each course. <br>
* Availability of demo sessions on weekdays as well as weekends. <br>
* Rescheduling of demo session if missed. <br>
* Multiple payment modes. <br>
* Installments availability on any types of payment mode. <br>
* Availability of both Online and Offline mode of training. <br>
* Updation can be performed on master table. <br>


### Getting Started
* enquiry table(ORC and master table)
Created student table having attributes ID,NameMail. Mobile_no, Course, Fee, Discount, Date Status,status_final

* Demo_Schedule table
It is taken from student table who has done their demo with added attributes like demoday (WD,WE),day,time


* demo_missed table
Data for this table taken from student table whose status is DND and adding attributes like string,reschedule_datetime


* enroll table
This table contains list of all the students who have enrolled and drop course.data taken from demo done table with some added attributes like payment_mode,total_installment,installment_paid,next_installment_date,payment_date,payment_status,installment_left,final_fee


* batch table this table contains details of students who joined training where data is taken from enroll table with added attributes like joining_date,week_day,day,time

## CONTRIBUTERS
* 1)KARAN JAIN
* 2)MOHAMMED ZAKIKAREEM
* 3)GAURAV MISAL
* 4)TRUPTI CHAUDHARI


## License
This project uses the following license: [MIT License](LICENSE)

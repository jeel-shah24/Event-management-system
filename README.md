# Event-management-system
sql database
DBMS PROJECT REPORT –
EVENT MANAGEMENT
Submitted by:        1) Jeel Shah(U101114FCS172)
                               2) Priyanka(U101114FCS074)
                               3) Marthala Supraja Reddy(U101114FCS091)
                               4) Mansi Mahesh singh(U101114FCS090)
                              5) Jallepalli Prerna(U101114FCS0174)








CONTENT

 1) INTRODUCTION

2) ER  MODEL

3) ER DIAGRAM

4) ER DIAGRAM TO RELATIONAL MODEL

5) NORMALIZING THE DATABASE

6) CONVERTING INTO RELATIONAL TABLES

7) SQL CODE

8) SOFTWARE USED

     9)OTHER DETAILS –TRIGGERS

INTRODUCTION
Database management systems(DBMSs) are specially designed software applications that interact with the user, other applications, and the database itself to capture and analyse data. The event management database we have it for event  managers. In this database manager will get every information about every event which is done and which are going on in future.
Database normalization is the process of organizing the fields and tables of a relational database to minimize redundancy. Normalization usually involves dividing large tables into smaller (and less redundant) tables and defining relationships between them. Most 3NF tables are free of insertion, update, and deletion anomalies
This project includes the program included that helps us to check which normal form dependencies of a table satisfy.
The objective of this project is to design the database event  Management Database which manages and stores all possible event  related informations. To find which Normal Form the dependencies for a particular relation lies in.

ESSENCE OF THE PROJECT

This project is especially designed for event managers.  The event manager will be able to feed in keep record and project reports of his work. It provides a user friendly approach for handling all the services .Some of the important features of the project are
Events:  gives information about all the requirements of services and products of the event being organized.
Reports:  reports can be generated for tracking success/process at different levels .
Vendor -Specific List:  generate specialized list of products and services ordered from a specific vendor.
Easy Tracking: keeps simplified track of employee /manager/ head appointed to an event.
Scope of Improvement:  allows for improvement by reviewing user feedback.

Present event managers (mostly small scale) face problems in tracking the requirements of an event when they are handling multiple events at a time. Special employees are also appointed  for managing the records for the events. The project provides an easy and automated approach that saves time, money, and mind-memory.
The project ensures real time feeding of data in a secure place which avoids data loss in offline logging due to any physical mishap and saves time wasted in unnecessary paper-work.
This project has been developed to overcome difficulties in utilization of present existing systems in general. Here users to the system are the event management company heads, managers and employees.
PROBLEM DESCRIPTION

This project is designed for event managers. The event manager will be able to feed in, keep record, project reports of his work. It provides a user friendly approach for handling all the services. Every event has its own  type, date, time, feedback, transportation charges ,budget  and an unique event ID. It has customers who can sponsor various events and have first name, last name ,address,  phone no, username ,password, discount  and unique customer ID. Every event needs various Electronic Equipments containing name, cost, unique ID, which are supplied by various Electronic companies having their unique ID, Address, email id ,name. For decoration purpose there are different types of decoration and their respective costs which will be supplied by different decorators having name, unique ID, mail id and address. Since there are many events held, each of these events are headed by one Manager.
Various employees are appointed to an event having first name, last name,unique E_ID, phone no, address, salary. These employees could be either managers or a part of the logistics team. Each Manager has an unique manager ID and department. Each of the logistics team members have work_ allotment and unique ID.
For making events more interesting informals are conducted. Every informal has its own unique informal ID , name, mail id, type, address. Events orders for the food of different types and their respective cost which is supplied by caterers who have their unique id, name, address, mail id. Each and every event is located at a particular venue .Venue is specified by its unique Id, name, capacity, rent, phone, address. Transportation is provided to an event is defined by the type of vehicle customer requires,cost per km  and the number of seats that vehicle has. Transportation is provided by Transport Company with name, id, phone number, address. Some events like stage plays, marriages require makeup. There are different make up services which will be provided and each of the makeup service has its own cost and type. The makeup artists are from parlours. Since there are different parlours, hence each of them has its own specific name, unique id ,mail id  and address. Since moments in the event have to be captured, so these are done by the photographers who cover the entire event. Each photographer has mail id , address, pay, ID, first name,lastname for further contacting.
For entertaining the guests in the event, different performances are held. These performances are performed in the event by performers who have their unique ID, name, salary, mail id  and address. Performers are classified into dancers, musicians, fillers and anchors. Each dancer has his/her unique ID and their forte. Similarly anchors have gender and unique ID. Fillers who help in entertaining the guests in the events appear in between the performances like mimicry, comedians etc who have their own unique ID and type. There will be music which will be performed and each different type of music has its unique music ID and type.

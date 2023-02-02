# Lab1_202001177
IT314-Software Engineering Lab-1 ( Identifying Functional and Non-Functional Requirements )


Q.1. Identify FRs and NFRs:

The institute has been recently set up to provide state-of-the-art research facilities in the field of Software Engineering. Apart from research scholars (students) and professors, it also includes quite a large number of employees who work on different projects undertaken by the institution. As the size and capacity of the institute is increasing with the time, it has been proposed to develop a Library Information System (LIS) for the benefit of students and employees of the institute. LIS will enable the members to borrow a book (or return it) with ease while sitting at his desk/chamber. The system also enables a member to extend the date of his borrowing if no other booking for that particular book has been made. For the library staff, this system aids them to easily handle day-to-day book transactions. The librarian, who has administrative privileges and complete control over the system, can enter a new record into the system when a new book has been purchased, or remove a record in case any book is taken off the shelf. Any non-member is free to use this system to browse/search books online. However, issuing or returning books is restricted to valid users (members) of LIS only.
The final deliverable would be a web application (using the recent HTML 5), which should run only within the institute LAN. Although this reduces security risk of the software to a large extent, care should be taken no confidential information (eg., passwords) is stored in plain text.


Ans )

→ Functional Requirements :

1) The System should authenticate and verify the user before enabling them to borrow a book

2) Issuing book is valid only for LIS member but any non LIS member is free to use the system and browse the books online

3) The web application should only run within institute LAN and can not be accessible from outside

4) There should be a backup for database so that incase of any problem data of the users and book remains

5) Librarians must have access to edit or delete any record.

6) A database log for all issued books. It must show available as well as not available (with available date) books for issue.


→ Non-Functional Requirements  :

1) Scalability : LIS system should be scalable so that if number of users increase in future the system should be able to handle without any issue

2) Usability : The website should be easy to handle and use.

3) Security : The system should be able to protect user’s sensitive information and data.

4) Portability : adding and updating new features to the software should be simple.

5) Concurrency : The system should be able to handle number of members at the same time

6) Performance : The latency and throughput of the system should be as low as possible

7) Maintenance : The system should be easy to update and maintain



Q.2. Identify scope, features and non-functional aspects of the following problem.

Approximately 5% of the world population (or a staggering 466 million people) suffers from
disabling hearing loss. We set out to create an impactful solution for this community that
addresses some of their everyday needs. Our mobile application uses artificial intelligence to
recognize key sound events of interest to this community, such as car horns and babies,
where immediate alerts and continual logging are critical for the user. This app is optimized
for Android with low-latency so that it works in real-time for use.


Ans ) 


Scope: 
-The scope of this project is to create a mobile application that addresses the everyday needs of people with disabling hearing loss. 
-The application will use artificial intelligence to recognize key sound events of interest to this community, such as car horns and babies. 
-The app will be optimized for Android devices and will work in real-time with low-latency.



Features: 
1)Successful Recognition of key sound events, such as car horns and babies. 
2)Immediate alerts when key sound events are detected. 
3)Optimized for Android devices with low-latency and high throughput for real-time use.



Non-functional aspects: 
1)Performance: The app should have a fast response time to ensure that sound events are recognized in real-time. 

2)Scalability: The app should be able to handle a large number of users and sound events. 

3)Usability: The app should be easy to handle and use 

4)Availability: The app should be accessible or available to users all time in any situation.

5)Maintainability: The app should be easy to update and maintain

6)Power consumption: The app should have minimum power consumption to ensures long battery life

7)Reliability: The app should be reliable and detect every sound events correctly








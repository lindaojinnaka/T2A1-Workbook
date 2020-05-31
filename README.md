# T2A-2 Workbook
## 1. Describe the architecture of a typical Rails application.
Word Count guide: 200-300 words <br>

The basic architecture of a Rails Application is composed using the MVC Framework. The MVC framework is an application design that consist of three parts- a  model, a view, and a controller, which are interconnected and work harmoniously to create an application with CRUD capabilities. CRUD refers to the four basic functions (create, read, update, destroy) used to operate on data and whose methods are derived from the Active Records of the rails application.   

The model is in charge of storing and managing data in the Rails application and ultimately defines the shape and structure of data in the application. Essentially, the Active Record is used to model the relationship between the databased used and the rails application.  

The controller of a Rails application receives specific incoming requests and defines what data the application needs.  

The view dispays information collected from the controller and renders that information to the user’s browser in human readable text. The views’ syntax is comprised of Embedded Ruby and HTML which is processed before being sent to the user. Helper methods are often used in the view to reuse code throughout the website and can be very beneficial when creating a basic form in HTML. 

https://edgeguides.rubyonrails.org/getting_started.html 

 
## 2. Identify a database management system (DBMS) commonly used in web applications (including Rails) and discuss the pros and cons of this database.	
Word Count guide: 150-250 words

PostgreSQL is an open source object relational database system where developers can manage data and build applications. In PostgreSQL, developers are able to define data types and functions, add new operators and index methods, and much more.  PostgreSQL also offers a wide range of advanced features such as foreign keys, transactional and data integrity, inheritance, and other services that simplify management and prevent data corruption.  

Transactional intgrity include row level security and GSSAPA and SSPI authentication to authentic users. Referential integrity check are also put in place to ensure prevent leaks and ensure data is protected from covert channels.  

Foreign keys improve the quality and performance of an application. A foreign key is a column or group of columns in a table that allows users to identify another row in a table. This can be useful because it reduces duplication in the user’s table and maintains referential integrity between the parent and child tables.  

Inheritance utilizes the object relational aspects of PostgreSQL by allowing tables to inherit column attributes, thereby creating a parent child relationship.  

Some drawbacks of PostgreSQL is poor speed performance when handling large amounts of data.  

 
https://www.postgresql.org/ 

https://www.postgresql.org/files/documentation/pdf/13/postgresql-13-A4.pdf 

https://www.postgresqltutorial.com/postgresql-foreign-key/ 

## 3. Discuss the implementation of Agile project management methodology.	
Word Count guide: 200-300 words <br>

The Agile method is a concept in project management that is aimed at garnering customer satisfaction by adhering to four principle values. The first value of the Agile method focuses on interactions and individuals over tools and process. Teamwork, collabaration, and face –to – face interactions are prioritized in order to ensure architectural requirements are being met and ample support is given to each member of the team. Daily collabaration also keeps indivuduals motivated on the task at hand.  

 

The second value focuses on functioning software over extensive documentation. Continual delivery of functioning software is essentially how progress is managed in the Agile method. Rather than delivering clusters of paperwork and documentation to the customer, functioning software is delivered instead, which has two benefits: It is a tangible result that will put the customers’ mind at ease when inquiring about progress, and it also keeps the software team on track towards delivering a final result.   

 

The third value of the Agile method focuses on customer collabaration. In the Agile method, the customer is placed as the highest priority, and therefore their concerns and demands are always addressed and implemented regardless of whether or not this changes the development/outcome of the project. The customer is allowed to make changes to an original plan and the team must adapt to the customers’ needs.  

The last Agile method focuses on being able to respond to change rather than following a concrete plan. This principle is essential in order for the previous value to be effective because adaptation would be impossible if a concrete plan were followed. Customers want to be given the ability to express their needs freely and change their mind on any previous specifications. If the team ignores the customers’ needs in order to churn out a product that was conceptualized months before, the project will no longer be satisfied or the customer may go elsewhere. Anticipating and responding to change also prevents months, if not years from being wasted because a product that is not flexible to change could potentially end up being eliminated.  

https://www.altexsoft.com/infographics/agile-project-management-methods/ 

https://www.agilealliance.org/agile101/12-principles-behind-the-agile-manifesto/ 



## 4. Provide an overview and description of a standard source control workflow.	
Word Count guide: 100-200 words

Git is an open source version control system with features such as local branching, multiple workflows, and staging areas.  

Git is a unique source control workflow in the regards to the way it handles data. Users have a local repository which can be private or public, that stores all incoming data.  Through the use of the “git add .”, “git-commit” and “git push” commands, users are able to upload their data to their local repository, which then effectively creates a series of snapshots over a projects’ period of time. This is extremely beneficial because it allows users to view changes over time, offline, in their own local repository.  

Two additional features of Git include merging and branching. Git allows users to create multiple independent branches that can also be merged. This is a huge benefit in regards to workflow because it allows a user to create a branch to experiment with an idea , commit to the branch, then switch back to where the user was experimenting and merge it in.

https://git-scm.com/about/branching-and-merging

## 5. Provide an overview and description of a standard software testing process (e.g. manual testing).
Word Count guide: 100-200 words

Software testing is the process concerned with planning and evaluating a product, component or entire system in order to ascertain if they are meet their specified requrement and are fit for intended use. Software testing is also conducted to detect bugs that may exist in the program and can be an invaluable tool for quality control.  

Genrally, the software in question will be run through the Software Life Cycle (STLC)
which is a sequence of steps taken to ensure the quality goals of the software are met. First, the testable requirements are identified. Next, test plan is prepared  and a strategy document is created. Essentially test plan defines the entry/exit criteria, the scope of testing, and the tools used to conduct the testing. Next, test cases are created, reviewed, and reworked if necessary. Smoke tests are then performed on the test enviroment to ensure the test enviroment is stable. A smoke test is a preliminary test that determines if the program is styable. Following the smoke test, the test is executed as per plan and all defects are mapped. Finally, a closure report for the test is prepared and assessments are given an overall pass/fall outcome. 


https://docs.google.com/presentation/d/1svLBhhx9BwgiDaiVhqjvguAsoaOCPN9h0ipobag9XwY/edit#slide=id.p
https://www.guru99.com/software-testing-life-cycle.html

## 6. Discuss and analyse requirements related to information system security and how they relate to the project.	
Word Count guide: 100-200 words

Fundamentally, information system security is a methodology that protects online data from unauthorized access. When creating a web application, developers must implement several practices from this methodology in order to prevent leaks, hacks, and outside interference with user information. 

Common methods used in network security in web applications, including my own Rails project are user authentication, encryption, and input validation to block malicious input from the user’s end.  

User authentication implementing user authentication to ensure user access is limited to their personal profile. In my application, I installed the ruby gem  "devise" which is a software that allows users of a web application to create an account, login, and log out of said account. One of devise's many strong points is that the software restricts users' from accessing and editing accounts that do not belong to them  

Devise also uses a password hashing algorithm named "Bcrypt" to secure passwords created by users. Through this process, the user's password is shielded by a randomly generated hash that is stored in the database. By doing this, no one, including the creator of the web application has access to the original password aside from its user. 

Input validation was also used in my project to block malicious input. 

https://www.freecodecamp.org/news/how-does-devise-keep-your-passwords-safe-d367f6e816eb/

https://www.lrswebsolutions.com/Blog/Posts/32/Learn-More/2018/11/11-Best-Practices-for-Developing-Secure-Web-Applications/blog-post/

## 7. Discuss common methods of protecting information and data and how you would apply them to the project.		
Word Count guide: 100-200 words
Two of the most common methods of protecting information and data that has been applied to my project is the cross origin resource sharing SQL injections and  policy.  

According to a report conducted by the CyberCX company names Sense of Security cross site scripting vulnerabilities were listed as of one of the top ten cyber security issues in 2018. A cross site scripting vulnerability is a type of web application vulnerability that enables attackers the ability to inject malicious client-side script that is then executed by a users’ browser, unaware to the user. This occurs when a user input is not “sanitized” and are able to insert their own HTML code. The attacker would then be able to access other pages. In order to protect from forged requests,Rails requires a security token that in its applications. By adding a security token, Rails will include it in all forms and generated AJAX requests. If the token does not match what is expected, Rails will render an error message. I would apply this to my project by including a security token to my application.  

 

In addition to cross site  scripting concerns, SQL injections were another cyber security issue identified in Sense of Security’s report.  

https://www.netsparker.com/blog/web-security/cross-site-scripting-xss/ 

https://dzone.com/articles/preventing-cross-site-scripting-vulnerabilities-wh 

https://guides.rubyonrails.org/security.html 

https://www.senseofsecurity.com.au/the-state-of-web-application-security-in-australia/#:~:text=Nearly%201%20in%202%20business,are%20vulnerable%20to%20cyber%2Dattacks&text=41%25%20of%20the%20findings%20show,a%20high%20risk%20of%20attack.
## 8. Research what your legal obligations are in relation to handling user data and how they can be met for the project.	
Word Count guide: 100-200 words
There are several steps that can be taken in relation to handling user to protect users’ personal information from unauthorized access, misuse, and modification. Some of the legal obligations in relation to handling user data that can also be met in project concern encryption and identity management and authentication  

Encryption is perhaps the most important legal obligation when handling user data because it ensures stored information cannot be easily deciphered by outside entities and unauthorized users. Encryption was met in this project through the use of the Devise gem which handled user accounts and password information. Devise encrypts user passwords by replacing them with randomized hashes that are stored in the database. That way, no one, including the creator of the database has access to the original password. Devise also sets the minimum requirements and standards of password complexity to ensure passwords cannot be easily guessed.  

Identity management and authentication is a process set in place to identify users accessing an application and controlling and restricting their access based on their identity. There should be proper access controls set in place that allows users to access, edit and delete their information, and only their information when accessing systems.   

https://www.oaic.gov.au/privacy/guidance-and-advice/guide-to-securing-personal-information/ 

## 9. Describe the structural aspects of the relational database model. Your description should include information about the structure in which data is stored and how relations are represented in that structure.
Word Count guide: 100-200 words

In Rails, the Active Record is the model of a developer’s database, and is responsible for representing the data and logic that is stored.  

The active record uses the technique of object relational mapping  which connects objects of an application to table in a relational database management system. Through the use of this framework, the Active Record gives users' procedures which include the ability to represent models and their data, represent associations between models, validation of models prior to persistence to databases, and more.  

Active record uses convention over configuration in Active Record which is applied in naming and schema conventions. Rails uses pluralization of class names in order to find corresponding data tables. For instance, a movie class in the database would have a database table of movies.  This is an example of how a relationship between a model and database table is created.   

 

Naming conventions also apply to primary and foreign keys. When a primary key is created, an integer column named “id” is created as the tables’ primary key. Foreign keys are to be given the underscore naming convention where words are separated by underscores. As a result, Active Record will search for this convention when creating associations between models.  

https://guides.rubyonrails.org/active_record_basics.html 


## 10. Describe the integrity aspects of the relational database model. Your description should include information about the types of data integrity and how they can be enforced in a relational database.
Word Count guide: 100-200 words
Data integrity refers to the maintenance of data and assurance the data is complete, consistent and accurate. Rails allows users to retrieve single source of data and  data  validation.  

Databases have ample amounts of data spread all over. It is important for a relational database to be able to retrieve a single source of data in a manner that is quick and easy, and rails implements this with finder methods whic allow users to retrieve objects from the database. 

Data validation is used to ensure that only valid data is saved to a database. For instance, it may be necessary for certain information to be required in a an application, and the developer would want to ensure that the information is not bypassed by the user. Validation helpers enforce this type of data integrity by preventing data to be persisted to the database when missing required, specified attributes.  

https://www.promptcloud.com/blog/7-steps-to-improve-data-integrity/ 

https://guides.rubyonrails.org/active_record_querying.html 

https://guides.rubyonrails.org/active_record_validations.html 

## 11. Describe the manipulative aspects of the relational database model. Your description should include information about the ways in which data is manipulated (added, removed, changed, and retrieved) in a relational database.	
Word Count guide: 100-200 words

The relational database model and its data structure are able to be manipulated through specific commands within the change method. Once these commands are input, the command “rails:db migrate” will make the necessary changes in the database.  


The change method is the main way to write several of these migrations. Commands  to add data into the relational database include:  

-add_index 

-add_reference 

-add_column 

-add_foreign_key 

-add_timestamps 


Commands to remove data from the Rails database include:  

-remove_timestamps 

-rename_column 

-rename_index 

-rename_table 

-remove_column (must supply a type) 

-remove_foreign_key (must supply a second table) 

-remove_index 

-remove_reference 

 

Commands to change data include:  

-create_join_table 

-create_table 

-change_column_default (must supply a :from and :to option) 

-change_column_null 

Alternatively, there are several finder methods that can be used to retrieve data such as find, group, from, annotate, extending, create_with, includes, join, and more.  

 

https://guides.rubyonrails.org/active_record_migrations.html 


## 12. Identify and explain the workings of TWO sorting algorithms and discuss and compare their performance/efficiency (i.e. Big O). 
Word Count guide: 300-500 words

According to the Big o lecture slide, “ A sorting algorithm is a set of steps to put a list of things in a specified order (like smallest to largest).  

Bubble sort is a comparison based sorting algorithm that takes Ο(n2). First, bubble sort checks to the first two elements next to each other and checks to see which one is greater. If the value of the first element is greater than the second element, the two elemennst are swapped. The next adjacent elements are compared, and if they are not in ascending order, they are again swapped. This continues until the array is completely sorted. This sorting algorithm is not ideal for big sets of data.  

Merge sort is the divide and conquer search method whose worst case time complexity is  O (n log n). Merge sort works by first dividing an array into two equal halves that can be called subarrays. The subarrays are further broken down into smaller subarrays until there are multiple subarrays with a single element and no more can be divided. Then, all the sorted subarrays must be merged step by step to finally form a single array.  

When handling smaller sets of data, the two algorithms performance are fairly similar. However, bubble sort and merge sorts’ performance differ greatly when sorting large sets of data. Merge set is able to perform consistently in respect to a large input whereas bubble sort is less time efficient when sorting large data. For instance, a merge sort with a data set of 1000 variables would need 3000 units of time/memory, whereas a bubble sort need 1000000. In this case, merge sort would prove to be the fastest algorithm.  

 https://www.tutorialspoint.com/data_structures_algorithms/bubble_sort_algorithm.htm 

https://www.studytonight.com/data-structures/merge-sort 

https://medium.com/@codeAMT/sorting-algorithms-the-difference-between-bubble-sort-and-merge-sort-bc91c3c2aff1 

https://durofy.com/differences-between-merge-sort-bubble-sort 

## 13. Identify and explain the workings of TWO search algorithms and discuss and compare their performance/efficiency (i.e. Big O).
Word Count guide: 300-500 words

According to the Big o lecture slide, “ A searchinh algorithm is a set of steps that are executed to find a value in a list of values. ”  

One example of a searching algorithm is in O(logn)- logarithimic. Binary search is an example of this O (log n). First, we start off with data that is given in an ascending or descending order. The first step in a binary search is to find the mid-point in the list and check it against the value given. Then, if the midpoint is equal to the value that the user is trying to find, the position is returned. However, if it is less than the midpoint, the action is repeated on the bottom half of the array. If it is greater than the midpoint, the same aciton is repeated on the top half of the array.  

Linear search is an algorithm in which a sequential search is performed by traversing through values one by one to find a particular value or element. First, a for loop is used to traverse the array. With each iteration, the target value Id compared with the current value. If the values match, the program will return to the current index of the array. If the value does not match, it will move to the next element.  

A binary search would prove more efficient in regards to performance because a search can be greatly reduced if found in the middle instead of searching one element at a time. Also, when a search is performed, a list is cut in half, and the search would only have to be done on half of a list. However, as the number of elements in a linear search increase, so does the amount of time it takes to search the elements. The worst-case complexity of a linear search is –O(n) while a binary search has a time complexity of O (log n). The main difference between the two is a linear search access information sequentially, while a binary search accesses data randomly.  

 https://www.tutorialspoint.com/data_structures_algorithms/linear_search_algorithm.htm 

https://www.studytonight.com/data-structures/linear-search-algorithm 

https://www.geeksforgeeks.org/linear-search-vs-binary-search/ 


## 14. Conduct research into a marketplace website (app) and answer the following parts: a. List and describe the software used by the app.50-100 per part 

Gumtree is an online classified, local selling site where users can list and sell items.  

Word Count guide: 50-100 per part 

a. List and describe the software used by the app. 

The software used by Gumtree includes Jquery, Nginx, React, Java, Jquery UI, Modernizer, Amazon CloudFront, Google Cloud Platform, and Select 2.  Jquery is a Javascript library which simplifies Javascript programming. Nginx is a web server that accelerates the performance of content on busy websites. Jquery UI is a curated set of widgets and themes using Jquery, CSS, and HTML. Modernizer detects which HTML, CSS, and Javascript features a visitors’ browser supports. Amazon Cloud Front is a service that accelerates the distrubition of dynamic and static online content to users. Google Cloud Platform enables users to build and deploy websites and services using the same infrastructure as Google. Select 2 offers customizeable select boxes for tagging, searching,infinite scrolling, and more.   

<br> <br> 

b. Describe the hardware used to host the app. 

Google Cloud Platform is a collection of Googles’ computing services that are made available to the public. Users of the platform interact with the VM (virtual machine) and are able to utilize services for data storage, machine learning, and data analytics. There are over 90 products under the cloud brand users that users can use to manage their services.  

<br> <br> 

https://en.wikipedia.org/wiki/Google_Cloud_Platform 
https://medium.com/@retomeier/what-is-googles-cloud-platform-d92a9c9e5e89 

c. Describe the interaction of technologies within the app. <br> <br> 

Bootstrap, JQuery UI. Select 2, React, and  Jquery make up the visual components of the applications, while Google Cloud Platform, Java, and Amazon Cloud Front handles the data and performance of the application.  

d. Describe the way data is structured within the app. <br> <br> 

In the Gumtree application, the main data that is displayed on the home page are the items on sale. The items are broken into categories which contain corresponding items for sale. There is also a search bar to find a particular item within the application. As a user scrolls down the page, tehre are cards which display sample items for sale along with a picture. Users who wish to sell items must sign up for an account in order to list their item. However, buyers do not need an account to purchase an item, they can simply contact the seller.  

e. Identify entities which must be tracked by the app. <br> <br> 

The entities that must be tracked in the app are the users which can be divided into two groups: buyers and sellers. When a user makes a post to sell an item, they are assigned a user id that is attached to their item. The listing is also tracked so that listings are updated asthey are created an deleted.  

f. Identify the relationships and associations between the entities you have identified in part (e). <br> <br> 

In the ERD, users can have more than one listing, but a listing cannot have more than one user. Also, a listing can have zero or many traits and a listing can also have zero or many listing traits.  

g. Design a schema using an Entity Relationship Diagram (ERD) appropriate for the database of this website (assuming a relational database model). 
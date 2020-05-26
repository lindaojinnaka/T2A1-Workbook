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

https://www.postgresql.org/files/documentation/pdf/13/postgresql-13-A4.pdf 

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

Git is an open source an open source version control system with features such as local branching, multiple workflows, and staging areas.  

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



## 7. Discuss common methods of protecting information and data and how you would apply them to the project.		
Word Count guide: 100-200 words


## 8. Research what your legal obligations are in relation to handling user data and how they can be met for the project.	

## 9. Describe the structural aspects of the relational database model. Your description should include information about the structure in which data is stored and how relations are represented in that structure.	

## 10. Describe the integrity aspects of the relational database model. Your description should include information about the types of data integrity and how they can be enforced in a relational database.

## 11. Describe the manipulative aspects of the relational database model. Your description should include information about the ways in which data is manipulated (added, removed, changed, and retrieved) in a relational database.	

## 12. Identify and explain the workings of TWO sorting algorithms and discuss and compare their performance/efficiency (i.e. Big O).

## 13. Identify and explain the workings of TWO search algorithms and discuss and compare their performance/efficiency (i.e. Big O).

## 14. Conduct research into a marketplace website (app) and answer the following parts:  a. List and describe the software used by the app.
  a. List and describe the software used by the app.
  <br> <br>

  b. Describe the hardware used to host the app.
   <br> <br>
  c. Describe the interaction of technologies within the app. <br> <br>
  d. Describe the way data is structured within the app. <br> <br>
  e. Identify entities which must be tracked by the app. <br> <br>
  f. Identify the relationships and associations between the entities you have identified in part (e). <br>  <br>
  g. Design a schema using an Entity Relationship Diagram (ERD) appropriate for the database of this website (assuming a relational database model).


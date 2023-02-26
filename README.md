# relationship-annotations
- project is based on showing the relationship annotations betwen diffferent classes
## Frameworks and Language used
* Springboot
* Java
## Controller
### StudentController
- Post Method
- getMethod(by id and getall)
- updateMethod or putMethod(by id)
- delete (by id)
### LaptopController
- Post Method
- getMethod(by id and getall)
- updateMethod or putMethod(by id)
- delete (by id)  
### BookController
- Post Method
- getMethod(by id and getall)
- updateMethod or putMethod(by id)
- delete (by id)
### CourseController
- Post Method
- getMethod(by id and getall)
- updateMethod or putMethod(by id)
- delete (by id) 
## Service
### StudentService
-  addstudent Method
- getstudentbyid
- getallstudent
- deletestudentbyid(by id)
- uodateStudent
### LaptopService
 - addlaptop Method
- getlaptopbyid
- getalllaptop
- deletelaptopbyid(by id)
- uodateLaptop
### BookService
-  addbook Method
- getbookbyid
- getallbook
- deletebookbyid(by id)
- uodateBook
### CourseService
- addcourse Method
- getcoursebyid
- getallcourse
- deletecoursebyid(by id)
- uodatecourse
## Repo
- here an interface is created for every model which intern extends JPA repository
* StudentRepo
* Bookrepo
* Courserepo
* Laptoprepo
## Model
- here creation of respective models are made whose tables are then shown by SQL.
## Database and design
### MYSQL and Table format
## DataStructure used
* Lists

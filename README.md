#This project covers basic hibernate concepts

###### Concepts Covered

1)CRUD operations  
2)Embedding value types  
3)Saving collections    
4)Eager and Lazy fetching  
5)Primary key auto generation strategy  
6)One to One mapping    
7)One to Many mapping     
8)Many to One mapping    
9)Many to Many mapping  
10)Cascade types  
11)Single Table strategy     
12)Table per Class startegy  
13)Joined strategy    
14)Transient, Persistent and Detached objects   
15)HQL and HQL pagination  
16)Named queries and named native queries    
17)Criteria API  
18)Restrictions  
19)Query by Example  


## Points to be noted

* Make sure MySQL DB server is running before running the test case. (using `systemctl status mysql`).
* Run individual test cases inside src/test/java/com/home/hibernate/test/HibernateTest.java as *JUnit test*.  
* TestCase name is self explanatory  
* Modify the hibernate.cfg.xml file as per your DB details  
* After running the test case, check the console output to understand the flow  
* Comment non related annotations (refer the entity class annotations and the test case)
* Uncomment the required annotations(refer the entity class annotations and the test case)

*Note: This project needs to be refactored to use best practices which will be done later. As of now this code should be used only for understanding purposes.*




* *Note: Run individual test cases instead of running all the test cases together to understand better. Comment non related annotations and uncomment required annotations by refering the test case and entity class so that you will not get confused.*  
 

* To install HSQL you need to install it via the command:
   -From GUI:
	 java -jar lib/hsqldb.jar &
   -Start Server:
	 java -classpath lib/hsqldb.jar org.hsqldb.server.Server &



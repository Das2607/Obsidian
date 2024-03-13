## Chapter 1


A **database** is a collection of related data.1 By data, we mean known facts that can be recorded and that have implicit meaning. For example, consider the names, elephone numbers, and addresses of the people you know. You may have recorded this data in an indexed address book or you may have stored it on a hard drive, using a personal computer and software such as Microsoft Access or Excel. This collection of related data with an implicit meaning is a database.

![](../../Images/Pasted%20image%2020240312232339.png)

DB properties:
- A database represents some aspect of the real world, sometimes called the mini-world or the universe of discourse (UoD). Changes to the mini-world are reflected in the database.
- A database is a logically coherent collection of data with some inherent meaning. A random assortment of data cannot correctly be referred to as a database.
- A database is designed, built, and populated with data for a specific purpose. It has an intended group of users and some preconceived applications in which these users are interested.

A database management system (DBMS) is a collection of programs that enables users to create and maintain a database. The DBMS is a *general-purpose software system that facilitates the processes of defining, constructing, manipulating, and sharing* databases among various users and applications.

- **Defining** a database involves specifying the data types, structures, and constraints of the data to be stored in the database. The database definition or descriptive information is also stored by the DBMS in the form of a database catalog or dictionary; it is called meta-data.
- **Constructing** the database is the process of storing the data on some storage medium that is controlled by the DBMS.
- **Manipulating** a database includes functions such as querying the database to retrieve specific data, updating the database to reflect changes in the mini-world, and generating reports from the data. 
- **Protection** includes system protection against hardware or software malfunction (or crashes) and security protection against unauthorized or malicious access.

### **Case study**

![](../../Images/Pasted%20image%2020240312234809.png)

- To define this database, we must specify the structure of the records of each file by specifying the different types of data elements to be stored in each record. We must also specify a data type for each data element within a record.
- To construct the UNIVERSITY database, we store data to represent each student, course, section, grade report, and prerequisite as a record in the appropriate file.
- Database manipulation involves querying and updating. Examples of queries are as follows:
	- Retrieve the transcript—a list of all courses and grades—of ‘Smith’
	- List the names of students who took the section of the ‘Database’ course offered in fall 2008 and their grades in that section
	- List the prerequisites of the ‘Database’ course


 Design of a new application for an existing database or design of a brand new database starts off with a phase called requirements specification and analysis. These requirements are documented in detail and transformed into a conceptual design that can be represented and manipulated using some computerized tools so that it can be easily maintained, modified, and transformed into a database implementation. The design is then translated to a logical design that can be expressed in a data model implemented in a commercial DBMS. The final stage is physical design, during which further specifications are provided for storing and accessing the database. The database design is implemented, populated with actual data, and continuously maintained to reflect the state of the mini-world. 

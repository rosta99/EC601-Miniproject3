# MongoDB vs. MySQL    
### Description     
this is a report of comparision of Mongo DB and mySQL for EC601 mini project 3.     
### User story for store data      
#### MySQL    
* As a manager at a stock trading institution, I would like to use mySQL to manage our accounting system, which can handle multi-row transsctions. 
* For medium-sized companies that need high-quality, professionally-managed database system with excellent support, MySQL is a better option.
#### MangoDB    
* As a user, I would like to modify my data schema without changing any of my existing data, so I will use mangodb.
* As an owner of a small business with rapid growth, I would choose Mangodb for it's easy management.
* For an app with real-time analytics, Mangodb is a better choice since it doesn't require schema definitions.
### User story for displaying data
#### MySQL
* As a manager, I'll choose mySQL over Mangodb cause I'd like to have my databases in a structured format.
#### MangoDB
* As a user, I'd like to have my databases in a more human readable format, thus I 'll choose Mangodb.
### Database of Mongo DB and my SQL
The biggest diversion of these two databases is mySQL is a Structured Query Lanuage(SQL), whereas Mango DB is a none structured one. This refers to different methods they use store data. MySQL is table based database, representing data in form of tables which consists of number of rows of data, whereas Mango DB is document based, collection of key-value pairs, graph databases or wide-column stores, which do
not have standard schema definitions which it needs to adhered to. One typical type of file that Mango DB uses to store data is json file.       
**MySQL**: MySQL has been maturing since 1995 and has grown a large following. It has been largely used in  legacy codes and 
Some organizations that use MySQL include Pinterest, Twitter, YouTube, Netflix, Spotify, US Navy, NASA, Walmart, and Paypal.     
MySQL is an open-source relational database management system. Just like all other structured query databases, MySQL uses tables, constraints, triggers, roles, stored procedures and views as the core components that you work with. MySQL mantains a schema table to keep all metadata related in other tables.

**Mango DB**: Unlike MySQL has a peroid of evolution and maturing, MongoDB wasreleased in 2009 and has been getting widely adopted to solve various business problems in the last several years. Now it is used by many organizations including Klout, Citrix, Twitter, T-Mobile, Zendesk, Sony, Hootsuite, SurveyMonkey, MuleSoft, Foursquare, and InVision.    
Since Mongo DB is none structured query databases, it can store related data together to improve query speed, which then can be accessed using Mongo DB Query lanuage. Mongo DB is also schema-free, allowing you to create documents without having to define the structure of the document first. These documents can be easily changed by adding or deleting fields.  
Another main benefit it has over MySQL is its ability to handle large unstructured data. It is magically faster because it allows users to query in a different manner that is more sensitive to workload.

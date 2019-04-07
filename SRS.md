# Inventory of movies
# Software requirements specification
# Introduction

## 1.1 Purpose 
The company(name of the company) of inventory of movies need a program where will be records the movements of the company
it will realize a inventory of movies with the purpose of save the records of input and output of movies, in the inventory of movies, 
there will be a lot of functions for different types of use. 

## 1.2 Scope 
 movie list is basically a program that realize the operating of records of input and output of movies, the users could 
 choose between movies of different categoies like terror, science-action, adventure, animation, biography,education etc.
 the project or the program is specifically designed for the employees and users 
 the users will have a email account where they can see the movies that are available and can set aside a movie for just arrive and take it
the employees of place will work with the system for keep the records of the company.

## 1.3 Definitions, Acronyms, and abbreviations
customers: a person or organization that buys goods or services from a store or business.
programmer: a person who writes computer programs.
collaborators: a person who works jointly on an activity or project; an associate.
employees: a person employed for wages or salary, especially at nonexecutive level.

## 1.4 References
IEEE SRS Format.

## 1.5 Overview
the main gaol of this project(system) is to help to keep a order in the products of the company.
this tool is quite useful for this situation since it will maintain a control.
in this case, the system must have a control of input and output of movies using a account to
see the latest news of the place.

# overall Description
In this part the lector will have a overview. in this section it will explain about the conexion of system(program), users and employees

## 2.1 Product perspecive 
the final product of the system consists in a program or application for modification and data management in where the system will has a conexion constant with database to keep it in a real time during the use and thus show the process of the changes so that others users can use it. 
The software system will work with SQL dtabase, communication in a red for submit te datos and registers 
the software system will be easy to use it , the system will be coded in c++ and java with connection a database
the sysyem will tell with a scanner for the product that are go out of place in rent. and the system will have a method of emergency in case of a dropped system


## 2.1.1 System Interfaces 

This should list each system interface and identify the functionality of the software to accomplish the system requirement and the interface description to match the system.

## 2.1.2 User Interfaces 
here there are 2 types of the user interfaces
employees: the implementation is about the almost complete use of the system, since the employees working for the registration of input and output of movies, help to customers to get information about the movies (if the movies are available or not) and 
customers: the customer can to get information in the plataform with its respective email and see all the news that are in the plataform 


## 2.1.3 Hardware Interfaces 
in this part just is necessary a computer for create the system and a red to keep a conexion with the system(database) and on the other hand


## 2.1.4 Software Interfaces 
the software interfaces 
users: it can to access to the platform if the user wants a movie aside since their cell phone usint the internet
employees: they can use the system for saved the information and to stock the behaivors that passed during the time of work 

## 2.1.5 Communication interfaces 
SQL database and connexion to red 

## 2.1.6 Memory 
122MB in RAM

## 2.1.7 Operations
the users can do different activities relatied with the system
the users can choose different types of movies for go with a employee and register the changes
too can have a email of the plataform for see the movies available and can to get a space available for apart the movie(s)
other operations is about the email, users can to get a email for see the last news of the company or place to what to go, 
users can synchronize it with its favorite email , too the user can access the platform on a specific page of internet 

## 2.1.8 Site adaption requirements  
a place in where it has a security for the system
## 2.2 Product funtions
there are two functions that the system must do:
employees: do the registration of the movies that the customers are taking 
manager: check every day if the program is working correctly 
help if someone needs it.

| Class of use cases|Use cases| Description of uses cases|
| ------------- |-------------|  -----|
|**Use case related to Installation**   |Installation of software necessary   |Software pre-installed on a main computer |
|**Use cases related to movie rentals**| categories must be shown|show the different available categories|
||show the price|display the price in each product|
||only rent of movies |customers can only rent the movies but not buy it|
|**Use cases related with the limit** |Customers hava a limit time|the customer must to give back the product in a time limit|
||Limit of movies| Customers only can to get 6 movies by day|
|**Use cases related with avaliable**|warning about movies| say it to the users if the movies are available for its use|
|**Use cases related to system database**|Login to the system database| Login into of the system during the time of working |
||records about movies| save the movies that are coming out and save the registers that are coming back |
||take dates about the movies| take all the datos of the movies, name, cost, categories,available, quantity and registes |

## 2.3 User characteristics 
In this part they are taking different types of actors which the customers and will take
charactetistics of the customers are :
it has the knowledges necessary for 
it has a method of page 
in the moment of registration, give information true the employee

administrator: he must of has the knowledge necessary to enter the system as administrator and keeps in order the system
it will check if the process of payment are working correctly 
it will check if the employees do good the work
it will check if the there is not problem with the system

employees: employees must help to the customers when they need it 
check if the system working correctly 
to update the plataform every day

## 2.4 Constrains 
one thing is about the time, if the company wants the system the most early possible, the developer will be very limit to not comply with the requirements
the developer can not user the system if there are a failure of electricity or failure in the red 
in case of use software specific, it has the license for can use it 

## 2.5 Assumptions  
that the company contributes with the artefacts necessary for the development of the system or it possible implementation 

# Specific Requeriments
A program that can relized input and outout of movies, the program will have a connexion with a database which keep in connexion with the system and thus the administrator and employees can do the changes such as registers the input and output the movies, to update the system for the news every day, check if the system haven't problem .
too that the customers will can use an email to enter the platform and know about the news of day
a tester for chech if the program works correctly 
that the program can registers the data of the customers for can to get the services of the company 
that in the moment that the customers to get a movie will be registered, who ask the movie, when and how many movies to got 
and the employees take the datos for the operation 

#Functional requirements
FR1: CRUD for Administrator:
the administrator can change,read,update and/or delete the products of the system 
the changes that are necessary to realized
FR2: place of help
the  customers can to access either in the plataform to get information or help in case of questions or in the place or establishement to get information
FR3: Search the product
the customer can search a product define it by its categories
FR4: information about the process of place(notifications)
the employees and the administrator will recive notifications about the input and output of the movies
FR5: check the products
the employees must organized the products sinces physically and in the system 
FR6: upgrade of system and plataform
the employees or administrator must upgrade the plataform and system for give the news about the movies




# Details
## Group No : 40
|Members                 |Rollno      |
|------------------------|------------|
|SAMPREETH JANGALA       |S20200010079|
|KARTHIKEYA BETHU        |S20200010090|
|NITISH REDDY NANDYALA   |S20200010142| 
|BASAVACHARI BOPPUDI     |S20200010043|
|HARITEJA UMMANENI       |S20200010076|

# Tools used
> We wrote the code in java language and used Mysql for database.
* Java
* Mysql

# Project Information
> We create the command line project for storing the Anime data in database.

In <font size= "3">"src"</font>  file we have sub pakages like

1. <font size="4">SQLDetails</font>
    >Mysql details here 
    - Details.java       
        > for storing SQL server credentials 
2. <font size="4">Run</font>
    > App.java and corresponding methods are here
    - App.java 
        > class that has main method.
    - Operate.java       
        > has methods that is called by App.java by corresponding command line arguments
3. <font size="4">Classes</font>        
    > We kept all classes here
    - Anime.java         
        > has details,constructors,methods of Anime class
    - Episode.java       
        > has details,constructors,methods of Episode class
    - Movie.java         
        > has details,constructors,methods of Movie class
4. <font size="4">Interfaces</font> 
    > we kept all interfaces here 
    - CONNECTable.java   
        > interface for getconnection
    - CRUDable.java      
        > interface for CRUD operations
    - FITERable.java     
        > interface for filter operations
5. <font size="4">Implementation</font>  
    > implementations of interfaces are in this directory 
    - AnimeCRUD.java     
        > implements CRUDable interface and has CRUD operations for Anime class   
    - ConnectionFactory.java 
        > implements CONNECTable interface to get connection with sql server.
    - EpisodeCRUD.java   
        > implements CRUDable interface and has CRUD operations for Episode class
    - MovieCRUD.java     
        > implements CRUDable interface and has CRUD operations for Movie class.
    - TestFILTER.java    
        > implements FITERable interface and has soring and filter operations for all there classes
6. <font size="4">CSV_files</font>  
    > all csv files here
    - Anime.csv          
        > csv file for Anime details
    - Episode.csv        
        > csv file for Episode details
    - Movie.csv          
        > csv file for Movie details
# To Run 
- To run the project download the code. 
- Then change the SQL server credentials in "./SQLdetails/Details.java" file.
- Run the "App.java" file in command prompt.
- It will display the details about how to get the data and insert the data and all.
 
# Sample-Hibernate-Code
save, update,delete,SaveOrUpdate,Get


firstly download oracle databade client and hibernate orm 
for ORACLE:http://www.oracle.com/technetwork/database/enterprise-edition/downloads/112010-win64soft-094461.html
for Hibernate:http://hibernate.org/orm/releases/5.2/
    download whichever version you want of both oracle and Hibernate
----------------------------------------------------------------------------------------------------
Add jars to our application by adding hibernate jars and ojdbc6 or ojdbc14 jars
paths for hibernate jars: <hibernate extraction instalarion directory>\hibernate-search-5.8.0.Final\lib\required\<all jars>
  
path for ojdbc6 or ojdbc14 jars:  <oracle instalarion directory>\oraclexe\app\oracle\product\11.2.0\server\jdbc\lib\ojdbc6.jar or ojdbc14.jar
  ---------------------------------------------------------------------------------------------
  Create user library in eclipse
  steps open Eclipse IDE
  Righr click on project->Build path->configure bulild path->Liabraries->add library->user library->next------>
    user Libraries->New<Enter Name>-->Add external jars<add above hibernate and ojdbc jars>->apply->apply and close..
  ********
  then after that directly add user library in your application.....
  ---------------------------------------------------------------------------------------------
 ///////////////////////////////////
  Create table as you want to map the records
  ex:SQL> create table product(PRODID number primary key,PRODNAME varchar2(10),PRICE float,QUANTITY number);
  ------------------------------------------------------------------------------------------------
    Then create files as given in project Repository,......
  ///////////best luck///////////////
  for running run the ClientApp file.........
  ========be patience first time it takes time to load libraries................
  ///////////////ALL SET/////////////////
  

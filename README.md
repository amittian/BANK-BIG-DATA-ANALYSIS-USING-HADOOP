# BANK - DATA-ANALYSIS-USING-HADOOP


A leading banking and credit card services provider is trying to use Hadoop technologies to handle and analyze large amounts of data.
Currently, the organization has data in the RDBMS but wants to use the Hadoop ecosystem for storage, archival, and analysis of large amounts of data.

TASKS and REQUIRMENTS :

>> Data Ingestion :

(a)  Bring data from RDBMS to HDFS. This data import must be incremental and should happen every 2 minutes

(b)  All these data must be encrypted in HDFS. The HDFS data should be compressed to store less volume.
The Sqoop password must also be encrypted

(c) The Sqoop password must also be encrypted

>> TOOLS & TECHNOLOGIES USED TO ACCOMPLISH THE TASKS 

(a) MYSQL -- must have access of DBs where Data are residing ,should familiar with Ad-Hoc analysis .

(b) SQOOP -- Data import(incremental) should happen every 10 minutes 

(c) CRONTAB -- in order  to automate SQOOP JOB for incremental import 

(d) HIVE -- Creating EXTERNAL HIVE table  and storing data in apropiate format ORC (recommanded ) for analysis 

(e) TABLEAU -- for Data Visualization ; should familiar with how to connect TABLEAU with HIVE table 

(f) R Programming -- Exploratory data Analysis
     
    NOTE : The use of ORC files improves performance when HIVE is reading , writing and 
           processing the data from large table
           
 >> BACKEND and UN-NOTICED EFFORTS 
 
          (a) written Java code for encryption / decryption of data before/after analysis ( MUST DONE) as per SLA
          (b) written Python code in order to covert small XML email files in to structured format and stored in HIVE 
             table for further analysis 
          (c) SQOOP password file must be encypted controlled with proper permission ,so 
              not everyone can access the client data stored in RDBMS  as per SLA
              
 
>>  CLIENT REQUIREMENTS :

          • Find out the list of users who have at least 2 loan installments pending.
     
          • Find the list of users who have a healthy credit card but outstanding loan account.
          
>> The following analysis done from survey ﬁles:

     • How many surveys got an average rating of less than 3, provided at least 10 distinct users gave the rating 
     • Find the details of the survey which received the minimum rating. The condition is that 
       the survey must have been rated by at least 20 users

     >> The organization also has lots of e-mails stored in small ﬁles. The metadata about the e-mail is present 
        in an XML ﬁle  email_metadata.xml
        Read the XML ﬁle for the e-mail structure and pack all the e-mail ﬁles in HDFS.
        
        • Which is the longest running e-mail? 
        • Find out the list of e-mails that went unanswered.

 



          

 
 
 
              
    
    

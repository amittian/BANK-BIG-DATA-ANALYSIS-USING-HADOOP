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

(b) SQOOP -- Data import(incremental) should happen every 2 minutes 

(c) CRONTAB -- in order  to automate SQOOP JOB for incremental import 

(d) HIVE -- Creating EXTERNAL HIVE table  and storing data in apropiate format ORC (recommanded ) for analysis 
     
    NOTE : The use of ORC files improves performance when HIVE is reading , writing and processing the data from large table
    
    

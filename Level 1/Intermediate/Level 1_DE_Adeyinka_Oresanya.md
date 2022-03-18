# Questions

### 1. In your own words, what are the difference between Data Engineering and Data Science.

**Data engineering** involves the development, construction, testing and maintenance of architectures such as databases and large-scale processing systems and the optimization of these databases for analytical processing and faster queries. Eseentially, data engineers ingest and store data in a way that will be useful for analysis. Whereas **data science** involves the mining of data in order to discover patterns that can provide insights, building predictive models using machine learning and developing tools to monitor essential business processes

### 2.	Why do you prefer Data Engineering?

I prefer data engineering because it is the foundation of data strategy for any organisation looking to make data-driven decisions. My current job involves the gathering and transformation of data and making it usable for analysis and drawing insights. I would like to know about this indepth, so as to be able to create data strategies and build data architecture for the organization I work for.

### 3. Name the important tools required to learn Data Engineering and how familiar you are with each ( Novice , Amateur, Fair, Good).
The imortant tools to learn are based on the data pipeline which is essentially the work of a data engineer:
| Tools | Familiarity |
| ----- | ----------- |
|Databases (MySQL, PostgreSQL) | Amateur |
| Processing tools (Apache Spark, Hive) | Amateur | 
| Scheduling tools (Apache Airflow, Oozie, Cron) | Amateur |
| Programming languages (Python , SQL) | Good |

### 4. Draw a flowchart for a typical ETL Pipeline.

### 5. Whats are the differences between the following (briefly describe and give difference): 

#### ETL Pipeline and ELT Pipeline
ETL (Extract, Tranform, Load) and ELT (Extract, Load, Transform)  are both forms of data integration with a key difference of having the three steps performed in different order. 

The **ETL** process is employed in Online Analytical Processing (OLAP) approach which require relational SQL-based data structures, for instance in data warehouses. Hence data brought into an OLAP data warehouse must first be transformed into a relational format before the data warehouse can ingest it for use in a business intelligence platform.
The **ELT** process, however,  is used in the Online Transactional Processing (OLTP) approach, e.g data lakes, which accept any kind of structured or unstructured data and don't require data to be transformed before loading it. Although data transformation is still necessary before analyzing the data with a business intelligence platform. However, data transformation occur after loading the data into the data lake. 

#### Data Warehouses and Data Lakes
A **data lake** is a repository for storing all types of raw data (structured, unstructured and semi structured) collected from different sources, which does not require any model or structure to store the data. This makes it cost-effective. Examples of data lakes include Azure data lake and Amazon S3. On the other hand, the data warehouse, as a data repository, stores specific data for a specific use and enforces a structured format, which makes it costly to manipulate but easier for analysing data. Examples include Amazon Red Shift.

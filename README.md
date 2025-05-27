
## Superstore Data analysis using AWS
This project showcases a basic data analysis pipeline using AWS services to explore and gain insights from the popular "Superstore" dataset. The workflow involves storing the dataset in Amazon S3, cataloging it using AWS Glue Crawlers, and querying the data using Amazon Athena. Additional analysis is performed using Python and Pandas to derive business insights such as sales trends, regional performance, and product profitability. This project demonstrates the power of serverless data processing and analysis using cloud-native tools.


## Dataset

The dataset used for the following project was taken from kaggle. The superstore dataset consists of varrious columns like Order , Order ID, Order Date, ship Date etc and has some missing values as well.
## Requirments
 Baisc knowledge of AWS (IAM, S3 bucket,Glue,Athena,Quicksight) 

### For data analysis
Tools like Pandas or NumPy can be used for data analysis and manipulation. 

### AWS For upoading and processing data
IAM,
S3 bucket,
AWS Glue,
AWS Athena,
AWS Quicksight


## Working
Once the dataset is cleaned and sorted, the next step is to upload the data into AWS cloud infrastructure. Amazon's S3 bucket is used for uploading data. AWS Glue is intialized to discover, prepare, and combine data from various sources and also has other features like analytics, machine learning, ETL, data cataloging, schema registry management,  and application development, a crawler is intialized to automatically discover and catalog data metadata, including schema and data format, within the bucket. At last, Athena is used for analyzing data using standard sql queries and quicksight to create dashboards and reports.

# AWS-Cost-analysis-project
Amazon Web Services (AWS) offers a robust and scalable solution for hosting Git repositories, providing a reliable platform for version control and collaboration. AWS CodeCommit, a fully managed source control service, allows users to store and manage Git repositories securely in the cloud. With features like automatic scaling, high availability, 
# Logical areas
Find latest manifest
Get the column names
Lowercase the names, replace : and - with _, add suffix to create unique names
Get the actual file paths
# Download the files
Download and unzip the files
Parse the csv data into individual json records
Send to ES
Based on the month, compute the index name.
Delete the index if it exists.
Create the index. Or not.
Send each record to ES. Maybe as a bulk request

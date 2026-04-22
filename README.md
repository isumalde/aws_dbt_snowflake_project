### DBT Core with AWS as my Data Lake and Snowflake as my Warehouse

This is the project where I learned how to work with AWS S3 as my data lake, snowflake as my data warehouse and set up my own dbt core project to do my data transformations. 

I have been using dbt cloud at work. In our company, each team's data analyst takes ownership of the team's semantic layer. But I wanted to build my own dbt core project and get comfortable with it. 

First, I learned how to create storage integrations in snowflake, create a stage, and establish trust between AWS and my snowflake account by creating an IAM role in AWS and giving that role permissions to read and write data to my S3 bucket. I would then established trust between AWS and my snowflake account by providing my storage integration's external ID and IAM user ARN to my role's trust policy. Then copy my ARN to my storage integration in snowflake.

 I have also created a key-pair authentication so that my dbt core project can run queries in my snowflake account. Z
 
I've gotten back to the basics such as what is the role of my dbt_project.yml, my profiles.yml and how to create my sources, how to run snapshots from ephemeral models to build my dim and fact tables. And finally create tests to check the quality of my data.

 After that, I have commited and merged my current branch's changes to my main branch and push that to my github repo.


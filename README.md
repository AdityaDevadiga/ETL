# TASK 1: ETL(extraction(AWS(s3) ==> transformation(add transformation) ==> load(load the data to local system) 

* Technology used : python(language),boto3 python library(library for extracting the data from aws s3 bucket),pandas python libarary(for reading
  the dataset and adding transformation on top of the dataframe  using the pandas ),colab python environment.


step1 : extracting  the data from the aws s3 bucket.

step2 : Add the transformation on the dataset.

step3 : output will storing to local system directory.


# TASK 2 : Extracting the data from the S3 bucket and based on the dataset counting number of the null rows , null columns  and empty cells in the dataset.

* Technology used : python(language),boto3 python library(library for extracting the data from aws s3 bucket),pandas python libarary(for reading
  the dataset and adding transformation on top of the dataframe  using the pandas ),colab python environment.


  step1 : extracting  the data from the aws s3 bucket.

  step2 : Add the transformation on the dataset that is :

          * Count the total number of rows in the dataset.
          * Count the number of rows with null or empty cells
          * Count columns with null or empty cells
          * Count the number of rows with all columns having values.
  
  step 3: Getting the all the count values from the step2 using python pandas library.and print the output in the console.


# TASK 3 : Extracting the data from the S3 bucket and based on the dataset counting number of the null rows , null columns and empty cells in the dataset USING PYSPARK.

* Technology used : Pyspark,s3a library for accessing the dataset from the aws account,DATABRICKS community edition.


  step1 : extracting  the data from the aws s3 bucket.

  step2 : Add the transformation on the dataset that is :

          * Count the total number of rows in the dataset.
          * Count the number of rows with null or empty cells
          * Count columns with null or empty cells
          * Count the number of rows with all columns having values.
  
  step 3: Getting the all the count values from the step2 using pyspark in databrick 
  community edition.and print the output in the console.


# TASK 4 : Extracting the data from the S3 bucket and based on the dataset counting number of the null rows , null columns and empty cells in the dataset and load the data into dictionary format in MONGODB ATLAS.

Technology used : python(language),boto3 python library(library for extracting the data from aws s3 bucket),pandas python libarary(for reading the dataset and adding transformation on top of the dataframe using the pandas ),colab python environment,pymongo library for connecting the mongodb atlas.

step1 : extracting the data from the aws s3 bucket.

step2 : Add the transformation on the dataset that is :

    * Count the total number of rows in the dataset.
    * Count the number of rows with null or empty cells
    * Count columns with null or empty cells
    * Count the number of rows with all columns having values.
step 3: Getting the all the count values from the step2 using python pandas library.and printing the data in MONGODB ATLAS.


Output Screen : ![Screenshot (5)](https://github.com/AdityaDevadiga/ETL/assets/72966036/f6bcfeec-498f-4b74-90dd-dffb1bd02405)

# TASK 5 : Extracting the data from the S3 bucket and based on the dataset counting number of the null rows , null columns and empty cells in the dataset and output will store it 'SNOWFLAKE DATAWAREHOUSE'
Technology used : python(language),boto3 python library(library for extracting the data from aws s3 bucket),pandas python libarary(for reading the dataset and adding transformation on top of the dataframe using the pandas ),colab python environment,SNOWFLAKE DATAWAREHOUSE

step1 : extracting the data from the aws s3 bucket.

step2 : Add the transformation on the dataset that is :

* Count the total number of rows in the dataset.
* Count the number of rows with null or empty cells
* Count columns with null or empty cells
* Count the number of rows with all columns having values.
step 3: Getting the all the count values that we can see in the snowflake environment.


Output screen : ![Screenshot (7)](https://github.com/AdityaDevadiga/ETL/assets/72966036/ea651fe0-d66d-4456-b868-2fc4c9b6f56e)

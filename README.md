# Big-Data-Challenge

For this project, the focus is on working with big data. These datas are usually too big to be running on local computer becuase of the lack of storage space or computation power. Pyspark is used to both help with extract and transform the data. The transform data is then loaded into postgressql which is hosted on amazon RDS. For reference, the data is from [here.](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)

The detail process is as below
- load in the data from amazon s3
- create a schema on sql database
- transform the data so the correct data type will be inserted into the database
- reduce the size of the data that is inserted

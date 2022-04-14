# Amazon_Vine_Analysis

## Overview of Project
The purpose of this analysis is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. PySpark, AWS, and Postgres were used to analyze Amazon reviews to determine if reviews from Amazon Vine members are biased.

## Deliverable 1: Perform ETL on Amazon Product Reviews

Create an AWS RDS database with tables in pgAdmin, dataset watches from the Amazon Review datasets, and extracted the dataset into a DataFrame.  upload the transformed data into the appropriate tables and run queries in pgAdmin to confirm that the data has been uploaded.

<img width="473" alt="image" src="https://user-images.githubusercontent.com/95591222/163298168-90fff223-6a13-460f-93f7-bd584e55f92d.png">
<img width="201" alt="image" src="https://user-images.githubusercontent.com/95591222/163298740-68f5a363-15bd-47cb-b5f6-6412e5aa4c23.png">

Then the data was extracted from the DF and used to make a new table.

## Deliverable 2: Determine Bias of Vine Reviews

Using your knowledge of PySpark, Pandas, or SQL, determine if there is any bias towards reviews that were written as part of the Vine program. Determine if having a paid Vine review makes a difference in the percentage of 5-star reviews.

<img width="516" alt="Results1" src="https://user-images.githubusercontent.com/95591222/163299767-a7c6ed5c-150a-49b5-b9a1-49d3c4a54611.png">
<img width="478" alt="Results2" src="https://user-images.githubusercontent.com/95591222/163299773-1388445e-0026-495d-8fe0-14b3a643a7e7.png">

* There were 959,125 Non Vine and 1,747 Vine Reviews. 
* There were 571,022 5 Star Non Vine Reviews and 605 5 Star Vine Reviews
* This analysis highlights that non Vine customers rate more frequently than the paid Vine customer.
* The percentage analysis tell us theat the paid reviews did not give out more 5 star reviews because it was paid.
* This leads us to the conclusion that there is no positivity bias in the Vine program. 

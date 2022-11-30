# Amazon_Vine_Analysis

## Project Overview
I've been tasked with analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. The steps we will take to analyze this dataset is:
  1. Perform the ETL process to extract the dataset
  2. Transform the data
  3. Connect to an AWS RDS instance
  4. Load the transformed data into pgAdmin
  
  ## Challenge Overview
    - How many Vine reviews and non-Vine reviews were there?
![Total_paid_Vine](https://user-images.githubusercontent.com/110737061/204926864-5969a465-84e4-4ba0-8aea-f0988297931b.png)
![Total_unpaid_Vine](https://user-images.githubusercontent.com/110737061/204926912-ab3b10f0-7881-469e-8363-dd2519e396c3.png)

  - How many Vine reviews were 5 stars?
![5 star](https://user-images.githubusercontent.com/110737061/204926982-2ec58142-65e0-4f22-abc7-fee6604c88d9.png)

  - How many non-Vine reviews were 5 stars?
![Unpaid 5 star](https://user-images.githubusercontent.com/110737061/204927054-d7761a6c-0905-4f36-8b46-a3d79ad7257b.png)

  - What percentage of Vine reviews were 5 stars?
![5 star percent](https://user-images.githubusercontent.com/110737061/204927097-f899647f-687b-42bc-9305-d33828a298c0.png)

  - What percentage of non-Vine reviews were 5 stars?
![5 star unpaid percent](https://user-images.githubusercontent.com/110737061/204927155-0bb6bfe5-b9ae-46b9-8dcc-3f12c98a69f5.png)

## Summary
Given the data provided, we can likely assume that there is positive bias for reviews in the Vine program. As stated above, the percentage of 5 star reviews is 51.1%, as opposed to the 38.7% non-Vine 5 star reviews. This clearly dictates a preference towards the Vine program. However, we can also see that there is only a total of 94 Vine reviews as opposed to the non-Vine reviews at a whopping 40471. There is a larger margine for the reviews to not be 5 stars so the percentage will much lower as opposed to the Vine reviews.

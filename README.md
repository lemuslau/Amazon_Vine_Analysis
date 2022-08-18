# Amazon Vine Analysis

## Project Overview

The intended purpose of this analysis is to idenitfy if there was a bias towards favorable reviews from the Amazon Vine Program when paid and unpaid. This analysis centered around a subset group for video games. For this analysis I used Google Colaboratory, Amazon Web Services to create a RDS group and a S3 bucket, PostreSQL, and PySpark.   

## Results: 

1. How many Vine reviews and non-Vine reviews were there?
- Of the total of 40,565 reviews, 94 were Vine reviews and 40,471 were non-vine reviews. 

<img width="350" alt="Vine Reviews" src="https://user-images.githubusercontent.com/102635884/185301131-0f6526ed-675a-45c5-9383-5ddd26213577.PNG">
<img width="350" alt="Non-vine Reviews" src="https://user-images.githubusercontent.com/102635884/185301273-af218554-030e-4db7-8eea-01b5a9f3e775.PNG">

2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- Of the 15,711 5 Star reviews, 48 were 5 star reviws from Vine users and 15,663 were 5 star reviews from Non-vine users. 

<img width="350" alt="5 star vine reviews" src="https://user-images.githubusercontent.com/102635884/185301784-401e0c8f-bf47-43be-bafc-427cb97b273c.PNG">
<img width="350" alt="5 star non-vine reviews" src="https://user-images.githubusercontent.com/102635884/185301810-4d6ecfdc-21f2-42bc-9b10-b74dc04cae65.PNG">

3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- 51.06% of 5 star reviews were from Vine Program paid reviews and 38.7% were from Non-vine unpaid users.

<img width="350" alt="Percentage Vine 5 Star" src="https://user-images.githubusercontent.com/102635884/185301994-83e380f2-8f5c-40ec-87aa-ba93e7a7a4ea.PNG">
<img width="350" alt="Percentage Non-vine 5 star" src="https://user-images.githubusercontent.com/102635884/185302031-fa1b5c02-79c1-4dac-856d-41fa60470a93.PNG">

## Summary:

Based off this analysis it can be concluded that there was positivity bias for reviews in the Vine progra. This is apparent through the percentages of each groups 5 star reviews where Vine revews were at 51% compared to non-vine at 38%. There is a possibilty that results can change if more data from Vine Users was recorded in the data because the current pool of data is significantly smaller than the non-vine users. Another way to use the dataset to support the analysis that Vine users were biased with positive results is through verified purchases. By filtering out the non-vine users, a majority of the vine users did not have a verified purchase. This is likely due to the fact that users are required to publish a review but does not confirmed they used the product.

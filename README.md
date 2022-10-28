# Amazon_Vine_Analysis
## Overview
This anaylsis was done to research the vine reviews on Amazon for the Home Improvement department. The data was uploaded from the S3 bucket link. Once uploaded, several tables were created from the data. The tables were used to find out how many reviews were vine vs non-vine and the percentages of each. These calculations will help determine if there is a positive bias for reviews in the Vine program.  

### Purpose
The purpose of the anaylsis was to use the following skills:
1. Google Colab
2. Amazon RDS
3. S3 buckets

### Results
Here are the results from the anaylsis of the Vine reviews for the Home Improvement department.

- **How many Vine reviews and non-Vine reviews were there?**
    - There are 266 Home Improvement Vine Reviews
    ![d2 1](https://user-images.githubusercontent.com/105830665/198695522-e9556816-e6ce-4627-b413-e57076d0f575.png)

     - There are 38,829 Home Improvement Non-Vine Reviews
    ![d2 2](https://user-images.githubusercontent.com/105830665/198699486-6fdb12df-752a-4433-a1a2-422188462516.png)

- **How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?**
     - The 5-star Vine reviews had a total of 125 reviews
    ![d2 3](https://user-images.githubusercontent.com/105830665/198698316-71c16e5d-d1e3-4eb7-87d1-d96c83bfbd41.png)

     - The 5-star Non-Vine reviews had a total of 18,246 reviews
    ![d2 4](https://user-images.githubusercontent.com/105830665/198699054-5ce55e67-1d45-48e3-9f04-3576052bdaf2.png)

- **What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?**
     - The percentage of 5 star Vine reviews were 46.9924%
    ![d2 5](https://user-images.githubusercontent.com/105830665/198699088-3709a796-5809-495d-949c-e62ba238542c.png)

     - The percentage of 5 star Non-Vine reviews were 46.9906%
    ![d2 6](https://user-images.githubusercontent.com/105830665/198698582-08e919f2-d4d9-4ea0-ae76-75ec81cae466.png)

### Summary
After conducting the analysis, there doesn't appear to be a positive bias for reviews in the view program. The 5-star percentage for the Vine reviews and Non- Vine reviews were extremely close, 46.9924% and 46.9902% respectively. In order to further understand, the analysis should conduct several additional calculations like:
- the percentage of 5-Star reviews aganist the total of reviews
- the percentage of 5-star reviews found helpful
- the percentage of 5-star Vine reviews found helpful vs the percentage Non-Vine reviews      found helpful.  
Adding these steps could further determine if there is a positive bias of the Vine review program.  



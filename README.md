# Amazon-vine-analysis

The goal of this project is to determine if there is any bias by reviews from the members of the Amazon Vine program. The Amazon Vine program is a service that allows manufacturers to revceive recviews from consumers for their products and usage experience. The Amazon Review data gathered for video using is using PySpark, and we are mainly focusing on the software product reviews. 

# Result
## Vine Reviews
![vine-analysis](Resources/vine-analysis.PNG)

Based on the calculations, there are a total of 248 reviews under the Amazon vine programs, with 102 reviews with 5 star reviews, and 41% of the total reviews are 5 stars. 

## Non-vine Reviews
![non-vine-analysis](Resources/non-vine-analysis.PNG)

Based on the calculations, there are a total of 17514 reviews not under the Amazon vine programs, with 5154 reviews with 5 star reviews, and 29% of the total reviews are 5 stars. 

# Summary

In comparison, there is a obvious bias for posiive reviews under the Amazon vine program, since the difference in percentage of 5 star views between vine and non-vine is about 12%. 

To further support the positive bias with the Amazon Vine program, we can perform additional analysis with the same produre for ratings that are lower than 5. With a wider scope of data and statistical analysis on lower ratings, we can determine with a better clarity if a positive bias exists with the Amazon Vine program. 

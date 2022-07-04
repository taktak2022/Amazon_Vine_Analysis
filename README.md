# Amazon_Vine_Analysis
# Module 16: BIG DATA (CLOUD COMPUTING)

## OVERVIEW
The purpose of this module was to explain in detail what BIG DATA is, what constitutes Big Data, it's infrastructure as it pertains to Big Data ecosystems such as Google COLAB and Amazon Web Services (AWS) and how it may be the future of data science industries.  It was a re-introduction of sorts as we all use or heard of the term "The Cloud" as it relates to computing but as ethereal as an actual cloud in the sky, most people do not have a clear understanding of it.  By using Spark, Hadoop and learning NLP: Natural Language Processing, we get a clearer understanding of this concept's implementation.


### TOOLS
* SPARK
  * MapReduce
  * PySpark
* Google COLABATORY
* Amazon Web Services (AWS)
  * RDS (Relational Database Service)
  * S3 (Simple Storage Service)
* SQL - pgAdmin

### RESULTS
NOTE: Of the 50 Datasets choices, I decided to choose "JEWELRY" due to my past experience from working at Tiffany & Co. in Hawaii and California.

* HOW MANY VINE MEMBER REVIEWS WERE THERE?
![VineMembers-TotalReviews](https://user-images.githubusercontent.com/99851509/177087639-c9de6d82-161e-415e-97f8-37e3169bea88.png)


* HOW MANY NON-VINE MEMBER REVIEWS WERE THERE?
![VineNonMember-TotalReviews](https://user-images.githubusercontent.com/99851509/177087701-c55a3ece-39a2-49db-8508-75e2035b97c9.png)


* HOW MANY VINE MEMBER REVIEWS WERE 5-STARS?
![VineMembers-Total5StarReviews](https://user-images.githubusercontent.com/99851509/177087820-7053819e-8c31-41ec-9cd4-cc0a7c19124f.png)


* WHAT PERCENTAGE OF VINE MEMBER REVIEWS WERE 5-STARS?
![Vine-5StarPercentage](https://user-images.githubusercontent.com/99851509/177087858-e57d54c6-a836-40f1-813e-be4c48b574f4.png)


* HOW MANY NON-VINE MEMBER REVIEWS WERE 5-STARS?
![VineNonMember-Total5StarReviews](https://user-images.githubusercontent.com/99851509/177087918-fe469d58-297b-4e49-8a43-771caa1a89c3.png)


* WHAT PERCENTAGE OF NON-VINE REVIEWS WERE 5-STARS?
![VineNonMember-5StarPercentage](https://user-images.githubusercontent.com/99851509/177088250-352147b7-27f4-4916-b20f-7228c845893d.png)


* HOW MANY NON-VINE MEMBER REVIEWS WITH A PURCHASE WERE THERE?
![VineNonMember-TotalReviews-withPurchase](https://user-images.githubusercontent.com/99851509/177088010-0153d718-ff7a-475f-a8f7-910316695e55.png)


* HOW MANY NON-VINE MEMBER 5-STAR REVIEW WITH A PURCHASE WERE THERE?
![VineNonMember-5Star-TotalReviews_with Purchase](https://user-images.githubusercontent.com/99851509/177088070-3f6cb45f-a54e-4764-b5c3-7c43a28f40dc.png)


* WHAT PERCENTAGE OF NON-VINE MEMBER 5-STAR REVIEWS WITH A PURCHASE WERE THERE?
![VineNonMember-5Star-withPurchase-Percentage](https://user-images.githubusercontent.com/99851509/177088104-6d3eb09b-f238-4fcf-8f35-329ba4897a18.png)


## SUMMARY
Amazon's VINE program is an invitation-only program that takes their most trusted Amazon reviewers to post opinions about products to help their fellow customers in making informed purchase decisions.  Once invited, the reviewers (called "VINE VOICES") are also offered complimentary products from Amazon's participating selling partners to try out and review.  Amazon does not influence or modify Vine reviews, both negative and positive as long as they comply with the company's posting guidelines. As such, the Vine program invitees need not necessarily purchase items to review them.  This point needs emphasis to understand the parameters of the calculations that were made (see above).
For the category I chose "JEWELRY", there does not seem to be many invited members of the VINE program or they do not purchase or are not gifted jewelry as a category to review as often as other categories.  This is evidenced by the overwhelming number of the non-Vine member total reviews 7689 as compared to the VINE member total reviews numbering only 21.  Both percentages of 5-STAR reviews from VINE members and non-VINE members were above 50%: 52% and 58% respectively but did not go above 60%.  Even those non-VINE members who did make a purchase and gave 5-STAR reviews came in at 59%.  This shows that there is no undue bias for reviews.  Unlike coffee or cosmetic product offers, offering complimentary jewelry may not be cost effective for those jewelry company partners of Amazon which explains the low number of VINE member reviews for this category.
Even in jewelry, there is high-end, for example diamond jewelry and low-end such as sterling silver jewelry with prices ranging from hundreds to thousands of dollars.  One recommended additional analysis would be to do a review breakdown by dollar amount: 
* CATEGORY 1: $0 - $300.00
* CATEGORY 2: $301.00 - $1000.00
* CATEGORY 3: ABOVE $1000.00



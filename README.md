# Autistic Spectrum Disorder Screening with Ensemble Majority Voting and Weighted Average Voting

<img src="/image.jpg" width="1000" height="300" />
<div align="justify">

## Ensemble Combination Rules
The machine learning classifiers can be combined using different combination rules i.e., Majority Voting and Weighted Average Voting.<br />

**Majority Voting**
Every individual model makes a prediction for each test instances and the final output prediction is the one that receives the majority of votes.<br />

**Weighted Average Voting**
In weighted average voting we can increase the importance of one or more models by assigning weights to the models. The prediction of each model is multiplied by the weight and then their average is calculated.<br />

## Dataset - Autistic Spectrum Disorder
Autistic Spectrum Disorder (ASD) is a neurodevelopment condition associated with significant healthcare costs, and early diagnosis can significantly reduce these. Unfortunately, waiting times for an ASD diagnosis are lengthy and procedures are not cost effective. The economic impact of autism and the increase in the number of ASD cases across the world reveals an urgent need for the development of easily implemented and effective screening methods. Therefore, a time-efficient and accessible ASD screening is imminent to help health professionals and inform individuals whether they should pursue formal clinical diagnosis. The rapid growth in the number of ASD cases worldwide necessitates datasets related to behavior traits. However, such datasets are rare making it difficult to perform thorough analyses to improve the efficiency, sensitivity, specificity and predictive accuracy of the ASD screening process. Presently, very limited autism datasets associated with clinical or screening are available and most of them are genetic in nature. Hence, we propose a new dataset related to autism screening of adults that contained 20 features to be utilized for further analysis especially in determining influential autistic traits and improving the classification of ASD cases. In this dataset, we record ten behavioral features (AQ-10-Adult) plus ten individuals characteristics that have proved to be effective in detecting the ASD cases from controls in behavior science.<br />

**Task:** Classification<br />
**Attribute Type:** Categorical, continuous and binary<br />
**Area:** Medical, health and social science<br />
**Format Type:** Non-Matrix<br />
**Number of Instances (records in your data set):** 704<br />
**Number of Attributes (fields within each record):** 21<br /><br />

**Attribute Information:**<br />
*Attribute Type:* Description<br />
*Age:* Number Age in years<br />
*Gender:* String Male or Female<br />
*Ethnicity:* String List of common ethnicities in text format<br />
Born with jaundice Boolean (yes or no) Whether the case was born with jaundice<br />
Family member with PDD Boolean (yes or no) Whether any immediate family member has a PDD<br />
Who is completing the test String Parent, self, caregiver, medical staff, clinician, etc.<br />
Country of residence String List of countries in text format<br />
Used the screening app before Boolean (yes or no) Whether the user has used a screening app<br />
Screening Method Type Integer (0,1,2,3) The type of screening methods chosen based on age category (0=toddler, 1=child, 2= adolescent, 3= adult)<br />
Question 1 Answer Binary (0, 1) The answer code of the question based on the screening method used<br />
Question 2 Answer Binary (0, 1) The answer code of the question based on the screening method used<br />
Question 3 Answer Binary (0, 1) The answer code of the question based on the screening method used<br />
Question 4 Answer Binary (0, 1) The answer code of the question based on the screening method used<br />
Question 5 Answer Binary (0, 1) The answer code of the question based on the screening method used<br />
Question 6 Answer Binary (0, 1) The answer code of the question based on the screening method used<br />
Question 7 Answer Binary (0, 1) The answer code of the question based on the screening method used<br />
Question 8 Answer Binary (0, 1) The answer code of the question based on the screening method used<br />
Question 9 Answer Binary (0, 1) The answer code of the question based on the screening method used<br />
Question 10 Answer Binary (0, 1) The answer code of the question based on the screening method used<br />
Screening Score Integer The final score obtained based on the scoring algorithm of the screening method used. This was computed in an automated manner.

</div>


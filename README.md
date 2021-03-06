# Predictive-Analysis-of-Fraudulent-Job-Postings

Data Understanding

For exploring the issue and further extrapolating knowledge from the data, the data understanding plays an important role. The dataset is taken Kaggle which consists of genuine job advertisements. The dataset contains a total of 17,880 job descriptions out of which 866 are fraudulent, whereas 17,014 are real from the period of 2012 to 2014. The dataset was already annotated if the job is fake or not on the basis of some suspicious activity by the client, incorrect contacts or wrong information about the company, complains made by the job seekers and some periodic checks. The dataset is seen to be highly unbalanced, contains a lot of duplicates and some entries have some blank fields on them. As a result of balancing, removing duplicates and removing some missing data a balanced corpus is found.

Data Preprocessing

Pre-processing is mandatory step required before a classifier is applied to the dataset. Nonetheless, the characteristics of the dataset are decided by the appropriate feature or variable choice technique to utilize through the model. The algorithm to predict the jobs nature is Random Forest Classifier for determining so as to recognize it is fake or legitimate. The process model can be led in the following four stages: pre- processing dataset, extracting attributes, classification and a detailed analysis. The first stage of pre- processing includes the content cleaning function and changing over the content in the structure appropriate to the classification. It incorporates getting rid of uninformative characters and words in the content along with noise extraction, for example, HTML labels, in which such words don't impact the overall direction of text.

ANALYSIS

The aim of this step is to construct a fundamental ruleset from a balanced dataset comprising of linguistic, relevant and metadata features obtained from measurable perceptions and exact assessment. In the following types of analysis, the real jobs are separated from the fake jobs and the different types will give a deeper insight into understanding the job.

QualitativeAnalysis

1. Geography based analysis:
Analysis can be made on the basis of Geography to understand where the maximum number of jobs are posted and the place which has the maximum number of fraudulent jobs posted. The first figure reflects the maximum no. of fake jobs are posted in the USA, followed by Australia and UK with the help of balanced data. The second diagram portrays the maximum number of job postings are in Australia followed by USA and other countries.
2. Text Analysis:
Meticulous job advertisements are more likely to be formulated by scammers for fraudulent companies. The job description which also consists the description of the company which is found to be sketchy and short. The benefits from the job and the requirements for qualifying for the job is left blank by the scammers. From the figure below the lesser fraudulent jobs have word counts greater 800. Most of the fraudulent jobs have a basic word count of 600. So, it can be concluded that fraudulent jobs have lesser description than the real jobs.
3. Binary Analysis
For binary analysis the columns with the binary outputs are considered. There are seven attributes that belong to this criterion. This section was discussed in the preliminary visualizations and an elaborate analysis will be done here. Attributes in this criteria are as follows: 
(a) missing logo for the corporate companies; 
(b) scammers did not add any screening questions; 
(c) scammers mostly added salary amounts on the title to attract job seekers; 
(d) features of the job were not designated which help in further categorization (i.e. education level, industry, experience level and the functions); 
(e) legitimate websites ask the candidates to apply to the company website bypassing the job board website or app; 
(f) the resumes are supposed to be sent on the personal emails directly; 
(g) the basic requirement for the education level is comparatively lower. The analysis found that most fraudulent companies do not have a logo for their company.

B. QuantitativeAnalysis

After performing a thorough literature review of related datasets and looking at the evaluations performed by them. At the end, Random Forest Classifier is seen to give better performance in terms of accuracy and precision. Most classifiers produced good results and their accuracies varied from 2 to 13%.

EVALUATION

In the final step of analyzations, Random Forest Classifier is applied on the unbalanced dataset which consists of 17,880 job records. The outcomes indicated that 81.76% of the jobs were grouped accurately. However, in further details the recall and precision for the legitimate class is 0.903 and 0.986 respectively. Despite of these numbers, the recall is 0.751 and the precision is 0.282. A screenshot of the confusion matrix shows 16,930 correctly predicted real jobs, 469 correctly predicted fake jobs, 64 incorrect real jobs and 397 incorrectly predicted fake jobs. Considering all the above perceptions, it very well may be expressed that utilizing unbalanced classifiers can give an exactness of a good level on a completely curated completely balanced dataset. With regards to recall, the examinations demonstrated that one job out of every ten jobs in a balanced dataset dodges the prediction procedure. To accomplish better outcomes and simplicity out the high instability of employment advertisements, it can be firmly accepted that the composite information from different domains about clients and organizations ought to be consolidated.

CONCLUSION

This paper shows the classification of the potential attributes of the employment scam, and the presented dataset of legitimate and false job postings, an openly accessible dataset from Kaggle containing both genuine real and false employment advertisements. As appeared, the online fraud related to recruitment is a relative new field of variable seriousness that can raise rapidly to broad scam. Additionally, exploring the basis of different attributes regarding the legitimate and false dataset. Pre-processing had to be done to achieve better accuracy as the dataset looked highly imbalanced. Some analysis is done based on Geography, word count, binary attributes and HTML attributes. The evaluation shows good results and can be applied to other datasets of this field to find out the precision and accuracy of the model.

FUTURE WORKS

The work can be extended to other datasets and advance the ruleset by concentrating on behavior of user, organization and system information just as client-content-IP impact designs. In addition, by utilizing chart demonstrations to investigate associations between fake job ads, organizations, and clients. Eventually, the aim will be proposing to build a commercial tool that is able to identify the fake jobs with complete accuracy so that job seekers are not exploited. an appropriate work extortion location device for business purposes.

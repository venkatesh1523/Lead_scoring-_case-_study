#Lead Scoring Case study

**Problem Statement**
An education company named X Education sells online courses to industry professionals. On any given day, many 
professionals who are interested in the courses land on their website and browse for courses. 
The company markets its courses on several websites and search engines like Google. Once these people land on the 
website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill 
up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company 
also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making 
calls, writing emails, etc. 

Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X 
education is around 30%. 

Now, although X Education gets a lot of leads, its lead conversion rate is very poor. For example, if, say, they acquire 
100 leads in a day, only about 30 of them are converted. To make this process more efficient, the company wishes to 
identify the most potential leads, also known as ‘Hot Leads’. If they successfully identify this set of leads, the lead 
conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads 
rather than making calls to everyone.


**Goals of the Case Study**

1. Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be 
used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most 
likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.
2.There are some more problems presented by the company which your model should be able to adjust to if 
the company's requirement changes in the future so you will need to handle these as well. These problems are 
provided in a separate doc file. Please fill it based on the logistic regression model you got in the first step. 
Also, make sure you include this in your final PPT where you'll make recommendations.

**Approach**

• Source the data for analysis
• Reading and understanding the data
• Data cleaning
• EDA
• Feature scaling
• Splitting the data into train and test dataset
• Prepare the Data for modelling
• Module building
• Module evaluation specificity and sensitivity or precision recall
• Making prediction on the test set

**Conclusion**

Based on the analysis, the most influential variables in identifying potential 
buyers, ranked in descending order of importance, are as follows:
  • Total time spent on the website.
  • Total number of visits.
  • Lead source: a. Google b. Direct traffic c. Organic search d. Welingak
    website
  • Last activity: a. SMS b. Olark chat conversation
  • Lead origin as Lead add format.
  • Current occupation as a working professional.
  • Taking these factors into consideration, X Education has a significant 
    opportunity to convert a majority of potential buyers by focusing on these 
    key aspects. By emphasizing the importance of the website experience, 
    the number of visits, various lead sources, specific last activities, lead 
    origin, and targeting working professionals, X Education can enhance its 
    chances of successfully converting potential buyers into customers

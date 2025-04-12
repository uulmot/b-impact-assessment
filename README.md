# b-impact-assessment

# The Impact of the Impact Assessment

## Introduction/Project Overview

I first encountered the B-Corp moniker on a bottle of hand soap (Dr. Bronner’s) at my local Target store and ever since, more and more of the certified “B” label are on different kinds of food products to even apparel stores like Patagonia and Allbirds that have front door signs with the label. B-Corp certification is a designation awarded to companies that achieve high standards of social and environmental performance, transparency, and corporate accountability (B Lab, 2025). Even if more companies are onboard to participate in this form of assessment to achieve the certification, it is important to understand if the financial results and practices being implanted in the companies are making a positive significant impact on the local to international economies they serve. In this analysis, I will work to explore all certified and even de-certified companies on their performance on the B Impact Assessment and also the following other topics:

•	Which industries perform highest in B-Corp certification overall and categorical scores.
•	Areas where most companies excel and where they struggle.
•	Trends in certification and de-certification over the years.
•	And which industries could the B-Lab organization try outreaching more to use the B Impact Assessment.


## Data Overview

### The dataset used for this analysis comes from the B-Corp Impact Data provided by B-Lab and is publicly available on their data.world page. Dataset has 134 fields and key ones that will be used in during this analysis are as follows:

•	date_certified, current_status, industry, country, size, overall_score, assessment_year, impact_area_(with 5 categories of impact), and impact_area_()_na_score (with 5 categories of impact)


## Data Methodology

### 1.	Data Cleaning: 
Since the dataset has been cleaned for use by B-Lab, there would only be removing the fields that will render irrelevant to the analysis that I will be conducting such as the fields that denotes “ia.”

### 2.	Data Transformation: 
After removing the fields of b_corp_profile, website, and all fields containing “ia” from Excel’s Power Query editor, in MySQL, I will be creating a table that has headers that will allow to have the edited dataset to be imported.


## Deliverables

### 1.	Documentation on project
### 2.	Data Dictionary on dataset
### 3.	SQL Queries File
### 4.	Visualizations on Tableau

## Results & Insights

### 1.
The growing number of certifications post-2020 highlights increased awareness and adoption of B-Corp principles. Declining de-certifications since 2020 suggests better retention of certified companies.

### 2.
Industries in food product, management consulting (for profits), advertising & market research are top leaders in getting certification while industries such as air transport, wind power generation, and fossil fuel power generation may suggest these industries that are more regulated have difficulty in getting certified.

### 3. 
It is clear that developed countries like the United States, U.K., and Australia lead in the number of companies certified, but it is the goal of the B-Lab organization to expand into more countries and also help out developed/developing countries like Vietnam, Iceland, and Czech Republic that may have government structures that do may lack the resources and education provided to their citizens for those interested in creating businesses that could possibly participate in the B-Corp certification.

### 4.
Data shows that about 77% of companies certified fall into the micro to small size in employee count. The rest of certified companies are medium to large size companies. This may suggest that the larger the headcount of a company, the more difficult companies are to get certified/re-certified because of the higher diligence required to meet with the B-Corp standards—cost too could be another important factor if the companies are seeking more funding and needing to save on operational expansion of the organization.


## Recommendations

### 1.
With industries such in food products or apparel, it is possible for certifications because it reaches to more customers (consumers) easily compared to industries such as in wind power generation or computer and electronic products. Marketing efforts regarding to more regulated industries could help expose more possibilities for companies to get the certification or improve company policies to align the principles of the B-Corp certification. 

### 2.
Over 70% of companies certified have about less than 100 employees. There could be efforts to get more larger employee size companies to have more efficient ways and possible to go through the certification compared to the smaller size companies. Though not mentioned in the dataset, assessing the total cost and resources used to go through the certification process could help understand what companies who are not able to get certified should do in the future. 

### 3. 
In the category of community, more companies that tend to have higher performing scores that are above 30-40 points compared to a category like governance. This could indicate that the priorities for businesses that are certified should focus on strengthening their work to keeping the company align with their mission and the values. Another category, in the environmental category, could mean the products and services provided should improve in their impact on how it affects to the environment and the consumers.


> **Correlation does NOT equal causation.**

---

## References

B Lab. (2025). B Corp certification demonstrates a company’s entire social and environmental impact. B Corp Certification demonstrates a company’s entire social and environmental impact. https://www.bcorporation.net/en-us/certification/ 

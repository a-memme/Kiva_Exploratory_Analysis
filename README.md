# Kiva Analysis
[Link to Tableau Dashboard](https://public.tableau.com/app/profile/andrew8402/viz/KivaLoanAnalysis_16394268628180/Story1)

## Analysis Overview 
- Using a dataset of Kiva.org loans issued over a two-year period, the following analysis explores how loans are distributed based on size, frequency, sector, location and theme type to gain further understanding of who, why, and how borrowers are receiving and using their loans.
- The following analysis dives specifically into average and total loan value by sector. Future analyses will eloborate further on average/total loan value by country, and will explore the implications of predictive analysis on repayment interval percentage. 

### Relevance 
- As a crowdfunding platform dedicated to extending support to financially excluded people across the globe, it is vital for a company such as Kiva to have a consistent and accurate grasp of some of these base concepts in order to help target sectors, communities, or even global locations in a meaningful and effective way.

## Targeted Variables 
### Loans by Sector 
- Average and total loans were calculated based on sector to gain a clearer perspective on which sectors/communities are seeking financial support most frequently and how taxing said loans are monetarily. 
- Understanding this relationship is vital for creating transparency for lenders, who may be committed to specific causes - knowing that their donation is being put to dedicated use - as well as in targeting potential Field Partners who may be associated with specific sectors.

### Loans by Country 
- Average and total loans were calculated based on location (country) to provide further insight on where funds are most popularly needed and, with the combination of sector information, why they are needed as well.  
- Such analyses could aim to identify areas of high/low demand, and provide groundwork in future analysis to understand the nature of the low demand areas (i.e whether they are underrepresented due to alternative factors, or whether the need for financial support is simply less as assumed).

### Repayment Intervals
- Tracking the proportion of different types of repayment intervals and their relation to other loan factors would be a very interesting and useful indicator to help provide lenders with transparency and confidence in monetary return for their donations.
- Future analyses will look to build an ML model (multi-targeted regression) predicting the category of loan repayment that each specific loan is likley to fall under. 

## Results 

### Average and Total Loans by Sector
Average loans (USD) as well as total number of loans disbursed were both analyzed based on sector (See Images and Tables Below)

#### Figure 1
![Screen Shot 2021-12-13 at 1 23 14 AM](https://user-images.githubusercontent.com/79600550/150733936-efc7b99b-9a06-4e6b-8887-11b0f46cd6d0.png)

#### Table A
<img width="230" alt="Screen Shot 2021-12-14 at 2 38 00 AM" src="https://user-images.githubusercontent.com/79600550/150734130-3d26e337-308a-4575-8f2d-04bc8a4d3ad6.png">

#### Table B
<img width="185" alt="Screen Shot 2021-12-14 at 2 37 02 AM" src="https://user-images.githubusercontent.com/79600550/150734156-0085a8f3-64ab-407d-b7b3-4de3f06a3a90.png">

Here, there is a tendency for some sectors with a high average loan value to have an extremely low total number of loans (i.e. Entertainment and Wholesale industries), indicating that loans needed in these sectors are quite expensive, however, the sector overall may not frequently need financial support. Other industries that follow a similar pattern in a less pronounced fashion include Arts, Clothing, Construction, Health, and Services – all with total loan values below sector average, and average loan values above sector average (See Figure 1). Finally, the Agriculture, Food and Retail industries show an interesting relationship as all three have an extremely high number of total loans allocated, and have somewhat modest average loan costs – just below overall sector average. Here, there is suggestion that such industries are most in need of financial support given their frequency of loans, even if their average costs are sometimes slightly low. 

In addition to sector interpretation, Figure 2 below depicts the number of loans allocated to different themes, providing a more specific depiction of how donations are being used. 

#### Figure 2
![Screen Shot 2021-12-14 at 2 40 19 AM](https://user-images.githubusercontent.com/79600550/150734279-e8903b0d-eddd-4377-bf00-29068f932f5d.png)

As the ‘General’ designation makes up for just over 50% of all loans, a secondary bubble chart is provided to break up the category and understand what the General label represents specifically (See Figure 3 below). 

#### Figure 3
![Screen Shot 2021-12-14 at 2 42 21 AM](https://user-images.githubusercontent.com/79600550/150734330-0f2aa2ac-6b48-4bb5-af66-56d87fea0b39.png)

Here, there are parallel findings to the previous graphs, showing a large frequency of loans in the Agricultural, Food, and Retail sectors, making up for approximately 75% of the total General categorization, and approximately 37% of total loans. Other themes of interest would be the Underserved population at 7%, as well as a number of themes within the 2-5% total loan range such as different forms of Agriculture, Higher Education, Water and Sanitation, Rural Inclusion, Vulnerable Populations, and General Women support.

## Summary of Analysis
The above results indicate a number of inferences about the data – namely that the Agriculture, Food and Retail industries are those that are consistently seeking financial aid. With this information, focus could be directed on creating greater awareness surrounding these industries through the Kiva platform in order to attract both lenders and potential Field Partners with common interests. Further analysis could also be performed in relation to repayment intervals and benefits in donating to these sectors to continue their promotion. Second, greater exploration of sectors experiencing a less pronounced disparity between average loans and total loans could be performed – such as Arts, Health, Clothing, Education, etc. – to determine whether these sectors are experiencing a lower volume of total loans due to lack of need, or a combination of other factors (i.e. accessibility, risk, etc.). Assessing concurrent themes in conjunction to these sectors could help paint a clearer picture of the reality behind this data as well. For example, themes within these categories that one may assume would likely be dealing with financial exclusivity  could be assessed – such as Extreme Poverty (0.64%) or Disaster Recovery (0.74%)  – and action such as outreach to relevant organizations could be performed to help increase accessibility. Limitations to this data, however, lies in the ambiguity of labels in loan themes. Many theme titles have overlapping meanings and may very well refer to the same or very similar causes. A look for future analysis here would be to amalgamate theme labels to create a more accurate representation of loans serving such themes.

Finally, for further data capturing purposes, information that would be helpful for future collection could be an expanded set of data points surrounding Field Partner information, such as names, sector/theme of focus, risk level and location (as depicted on the Kiva website) to help organize a clearer depiction of borrower support in specified industries. With this additional data, many of the proposed analyses mentioned above could be performed efficiently, and will work toward creating a stronger understanding of the why’s behind the average loan vs. total loan relationship when considering sector and themes.

*Future additions to this analysis will include in-depth results into average/total loan values by location (country) and predictive analysis on repayment intervals. To view a more complete representation of visualizations (including maps for loan values by country) [click here](https://public.tableau.com/app/profile/andrew8402/viz/KivaLoanAnalysis_16394268628180/Story1) to view the Tableau Dashboard.*

# Kiva Analysis
[Link to Tableau Dashboard)
(https://public.tableau.com/app/profile/andrew8402/viz/KivaLoanAnalysis_16394268628180/Story1)

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



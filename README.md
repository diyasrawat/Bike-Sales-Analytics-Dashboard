# Bike-Sales-Analytics-Dashboard

# Project Overview
This interactive Microsoft Excel dashboard provides insights into customer behaviors, preferences, and trends to help guide data-driven product and marketing decisions.

The dashboard enables users to:

1. Explore the underlying dataset of bike buyer information through intuitive filters in Excel
2. Visualize key performance metrics for different customer segments using Excel charts
3. Analyze the popularity of bike models across age groups, regions etc using Excel pivot tables
4. Spot changes over time in purchasing patterns via Excel graphs and conditional formatting
5. Identify behavioral differences across demographics using stacked columns and more
6. This addresses the need for actionable bike buyer analytics direct in Excel, allowing decisions makers to conduct segmentation and analysis dynamically. Rather than relying on intuition or static reports, interactive dashboards empower self-service investigation.

By surfacing hidden insights, both strategic and tactical business decisions can be optimized based on statistically significant trends. This is facilitated through Excel's powerful visualization, pivot table, and filter capabilities.

# Dataset Overview
This dataset contains details on 1,000 bike buyers to analyze purchasing patterns.

1. ID - Unique identifier for each customer.

2. Marital Status - Indicates if the customer is single or married

3. Gender - Customer identified gender as male or female.

4. Income - Yearly individual earnings of customer.

5. Children - Number of children the customer has.

6. Education - Highest education level attained such as high school , partial college, bachelors or graduate degree

7. Occupation - Job role held by customer.

8. Home Owner - Categorizes if customer owns or not their residence.

9. Cars - Number of automobiles owned by the individual.

10. Commute Distance - One way commute trip mileage traveled daily.

11. Region - Geographic area the customer resides in such as pacific, europe or north america

12. Age - Age of customer in years.

13. Purchased Bike - Boolean flag noting if customer has purchased bike or not

# Steps to Create an Interactive Dashboard

1. Clean and normalize data

2. Structure data tables

3. Identify metrics and visualizations

4. Configure sheet linkages

5. Design clear visualizations

6. Add interactivity via filters, slicers

7. Enable click-through navigation

# Concepts Used

1. Descriptive Analytics
The dashboard utilizes descriptive analytics techniques like measures of central tendency, dispersion, distributions to summarize patterns in dimensions like customer age, income, and purchase frequency. Helps surface overall trends.

2. Data Visualization Principles
Charts and graphs like bar plots, histograms, scatter plots have been thoughtfully selected and designed based on data visualization best practices to transform bike buyer data into intuitive insights.

3. Interactive Data Exploration
Excel interactivity features enable end-users to dynamically filter, segment, and explore data on the fly without dependency on static reports. Empowers self-service investigation.

4. Aggregation and PivotTables
Aggregating metrics and pivoting transactional data faciliates analysis across multiple dimensions to uncover insights by age group, location, income bracket, and more bike buyer attributes.

5. Correlation Analysis
Statistical techniques help quantify and visualize the strength of relationships between dimensions like product preferences and demographics, purchase history and lifecycle stage.

# Insights 
**1. Bar Chart (Marital Status):** 

**Question:** How does the count of bike purchases vary among different marital statuses? Are married individuals more likely to purchase bikes?

**Answer:** Analysis of bike purchase data segmented by marital status indicates that single individuals purchase bikes at a higher rate than married individuals. Out of the sample, 249 single people made a bike purchase compared to 212 single people who did not purchase a bike. For married individuals, 232 made a bike purchase out of a total of 307 married people in the sample. This indicates that 54% of single people purchased a bike [(249)/(249+212)], while only 76% of married people made a bike purchase [(232)/(232+307)]. Based on this data, single individuals show a greater propensity for purchasing bikes compared to married individuals.  This indicates that marital status appears to have an association with likelihood to purchase a bike, with single individuals more frequently making bike purchases compared to married individuals.

**2. Bar Chart (Gender):**

**Question:** Build a bar graph to compare the count of male and female customers. Does gender influence bike purchases, and if so, to what extent?

**Answer:** The bar graph compares the count of female and male customers who purchased a bike. It shows 242 male customers made a bike purchase, while 239 female customers made a purchase.
Though more males bought bikes than females, the difference is small (242 male buyers versus 239 female buyers). Calculating purchase rates shows that 48% of males [(242)/(242+267)] and 49% of females [(239)/(239+252)] made a bike purchase. This minor 1 percentage point difference in purchase rates suggests gender does not largely influence the likelihood of buying a bike based on this data. Hence, the fairly equal bike buying rates implies gender itself does not greatly sway the probability of whether someone will purchase a bike.

**3. Histogram (Income):**

**Question:** What is the distribution of income among bike buyers? Are there specific income brackets that show a higher likelihood of bike purchases?

**Answer:** Of the various income brackets, the middle range between Rs 70,000 to Rs 1,00,000 accounts for the highest raw number of bike purchases in the sample, with 28 total buyers. Seventeen purchases occurred in the brackets between Rs 70-80K, while another 11 buyers had incomes of Rs 90-1,00K. This data distribution suggests those in the middle income levels may have a greater tendency to buy bikes. The higher count of buyers at the Rs 70-100K range indicates middle income customers likely have a higher purchase likelihood based on this sample.

**4. Histogram (Age):**

**Question:** Create a histogram to understand the age distribution of bike buyers. Are certain age groups more inclined to purchase bikes?

**Answer:** Histogram of bike purchases by age shows the distribution spans from 25 to 76 years old. Analyzing specific 5-year age bands indicates the 34-38 age range exhibits the highest buyer count:

•	Age 34 buyers: 19

•	Age 35 buyers: 22

•	Age 36 buyers: 31

•	Age 37 buyers: 29

•	Age 38 buyers: 29

This 34-38 bracket accounts for 130 total bike purchases in the sample. The age groups of 43 and 47 also show elevated counts, with 19 and 20 purchases respectively.
In aggregate, the 5-year bands spanning ages 34-38 demonstrate the greatest raw number of bike buyers. This suggests people in their mid-30s to late-30s have the greatest inclination to purchase bikes based on the observable distribution. Ages 43 and 47 also emerge as local peaks for bike buying activity.

**5. Box Plot (Income):**

**Question:** Identify outliers in the income distribution of bike buyers. Are there any extreme income values, and how might they impact purchasing behavior?

**Answer:** The box plot “Income” shows the distribution of income among bike buyers. The median income is around 60,000 and the interquartile range extends from approximately 40,000 to 80,000 1. There are three outliers above the upper whisker, indicating individuals with incomes significantly higher than the majority, specifically around 140,000 to 160,000 12. These extreme income values might indicate a small group of bike buyers with a significantly higher income, which could potentially impact purchasing behavior by:
a) Skewing average income calculations higher than the true central tendency among the majority of purchasers and indicating a wider range of bike affordability among buyers.
b) Indicating there may be greater price flexibility and willingness-to-pay at the very upper income bands, which widens the affordability range that manufacturers can consider in product design and segment-level pricing decisions.

**6. Pie Chart (Region):**

**Question:** Represent the distribution of bike purchases by region using a pie chart. Are there regions where bike purchases are notably higher?

**Answer:** The pie chart is showing the percentage of total bike purchasers that are accounted for by each region.

Europe

•	Bike Purchasers: 148

•	% of Total Purchasers: 31% (148/481)

North America

•	Bike Purchasers: 220

•	% of Total Purchasers: 46% (220/481)

Pacific

•	Bike Purchasers: 113

•	% of Total Purchasers: 23% (113/481)

To summarize the pie chart:

•	North America makes up the highest proportion of total bike purchasers at 46%

•	Europe represents 31% of total bike purchasers

•	Pacific comprises 23% of all bike purchasers

**7. Scatter Plot (Income vs. Age):**

**Question:** Create a scatter plot to investigate the relationship between income and age. Do individuals with higher incomes tend to be in specific age groups?

**Answer:** This scatter plot “INCOME VS AGE” investigates the relationship between income and age. The x-axis represents income, ranging from 0 to 200,000, while the y-axis represents age, ranging from 0 to 100. The blue diamond-shaped points scattered across the graph represent individual data points. Data points are densely packed between the ages of around 30 to 70 and income levels between approximately 50,000 and 150,000. There is no clear pattern or correlation visible that indicates a specific age group has a significantly higher income 1. The spread of data points at varying ages across higher income values implies there is no strong correlation or tendency for specific age brackets to have significantly elevated incomes.

**8. Stacked Bar Chart (Marital Status & Gender):**

**Question:** How does the distribution of bike purchases differ when considering both marital status and gender simultaneously? Are there notable patterns?

**Answer:** Among females, single women demonstrate a higher bike purchase rate (130 purchasers out of 250 total single females) compared to married women (109 purchasers out of 241 total married females).

Similarly for males, singles also exhibit a greater propensity to purchase bikes - 119 single male buyers out of 211 total compared to 123 married male buyers out of 298.

So across both genders, single individuals purchase bikes at higher rates than married people. This aligns with earlier analysis that singles overall have greater inclination for bike purchases irrespective of gender.

Additionally, when looking within marital status brackets, female purchase rates are slightly higher than males amongst both married and single segments.

109 married women bought bikes out of 241 (45% rate) versus 123 out of 298 married men (41% rate).

And 130 single females purchased out of 250 (52%) compared to 119 of 211 single males (56%).

So the intersectional analysis reinforces singles as highest likelihood bike buyers. It also reveals married and single females edge out their male counterparts slightly in conversion within those marital groups.

**9. Correlation Heatmap (Numeric Variables):**

**Question:** Use a heatmap to visualize the correlation matrix between numeric variables. What variables show a strong correlation, and how might this influence purchasing behavior?

**Answer:** Correlation Matrix

Income & Age: 0.16

Income & Cars: 0.45

Income & Children 0.26

Age & Cars: 0.19

Age & Children: 0.53

Cars & Children: 0.27

**Key Trends:**

Strongest correlation between Age and Children (0.53)

Secondary moderate correlation between Income and Cars (0.45)

These relationships influence bike purchasing behavior in the following ways:

1. Older buyers at a parenthood life stage will factor priorities like child safety, storage capacity, and durability/reliability into purchase decisions. Marketing and product design catering to family practicality will resonate most.
2. Higher disposable income allows greater ability to spend on premium bike features, accessories, or own multiple bikes per household member. Tiered pricing and upsell opportunities should target higher income segments accordingly.
In summary, the correlations related to buyer life stage and affluence suggest taping into family-oriented messaging and tiered pricing to income are likely the most impactful strategies influenced by the observed data relationships.

# Recommendations

**1. Marital Status Bar Graph**

a) Target singles in marketing as prime buyer profile

b) Cater product mix and pricing to young professional segment

c) Analyze barriers for married individuals

**2. Gender Bar Graph**

a) Adopt gender neutral marketing approach

b) Design inclusive retail environments

c) Offer consistent pricing across genders


**3. Income Histogram**

a) Isolate and target mid-income bracket

b) Price-match to income constraints

c) Analyze high-end outlier behavior

**4. Age Histogram**

a) Focus marketing on professionals and parents

b) Connect safety and reliability to families

c) Study loyalty opportunities

**5. Region Pie Chart**

a) Prioritize North America and Europe for growth

b) Customize product catalog and promotions by region

c) Investigate higher Pacific preference

**6. Box Plot**

a) Segment ultra high income buyers

b) Develop premium pricing offerings

c) Create targeted upsell campaigns

**7. Scatter Plot**

a) Perform multivariate regression analysis

b) Expand analysis beyond two variables

c) Test for other hidden relationships

**8. Correlations**

a) Align marketing to family utility messaging

b) Offer dynamic loyalty programs

c) Provide tiered pricing by income

# Conclusion

1. Single individuals have the highest bike purchase rate, presenting a prime target segment

2. Gender itself has minimal impact on likelihood to purchase

3. Mid-income buyers account for significant volume share

4. Parents and young professionals represent focused demographics to engage

5. Customization to regional preferences is required

# Future Scope

Further studies can harness more granular data and advanced analysis techniques to derive deeper insights:

1. Demographic intersections beyond standalone cuts

2. Psychographic analysis tied to attitudinal factors

3. Formal statistical modeling to quantify effects

4. Wider economic data integration

5. Ethnographic research on barriers and unmet needs

These expansions can uncover more nuanced relationships and premium micro-segments while guiding product-market fit and go-to market strategy. Advanced analytics and datasets focused on the customer journey will proliferate actionability. The current analysis provides a meaningful baseline level view into multiple core demographic dynamics strongly tied to bike purchase propensity and behaviors. Further extending the lens will boost precision.



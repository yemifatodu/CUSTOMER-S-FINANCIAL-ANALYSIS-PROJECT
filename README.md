# CUSTOMER'S FINANCIAL ANALYSIS PROJECT

## INTRODUCTION

Welcome to my shop's customer data analysis report of an imaginary shop's target customers, where I explore the nuances of a shop's customer base dataset. Through this analysis, I aim to uncover invaluable insights that can empower businesses, including yours, to gain a deeper understanding of their clientele and enhance their customer experience strategies. The dataset, sourced from Kaggle, comprises 2000 entries across 8 columns, encompassing essential customer attributes such as gender, age, annual income, spending score, profession, work experience, and family size.

![CUSTOMER FINANCIAL ANALYSIS STOCK PHOTO](https://github.com/yemifatodu/CUSTOMER-S-FINANCIAL-ANALYSIS-PROJECT/assets/147722919/91d891fe-68a8-4c5e-aab4-a68b6b3b6844)


**PROBLEM ADDRESSED BY THE DATASET**

The dataset is designed to answer a fundamental question faced by businesses: how can insights derived from customer demographics, behavior, and spending patterns be leveraged to effectively cater to and enhance the clientele's experience? By analyzing these aspects, businesses can tailor their marketing strategies, product offerings, and overall customer engagement efforts to align with their customers' preferences and needs, ultimately leading to improved customer satisfaction and loyalty.


**CHALLENGES ENCOUNTERED**


One notable challenge faced during this analysis was the task of categorizing customers according to their income levels. By adhering to guidelines from reputable sources such as the Pew Research Center and US News and World Report, I established income brackets to segment customers into low, middle, and upper-income categories. This process required additional data manipulation and the creation of an "income bracket" column.

Another hurdle arose when creating age brackets using the vlookup function, resulting in 35 blank cells. To address this issue, I utilized Excel's functionalities to identify and populate these blank cells, ensuring the completeness and accuracy of our data.

**MY ROLE AS DATA ANALYST**

As a data analyst for this project, here are the key aspects of my role:

1. **Data cleaning and preparation:** I ensure that the dataset is clean, accurate, and ready for analysis. This involves identifying and addressing data inconsistencies, missing values, and outliers, as well as structuring the data for efficient analysis.

2. **Data transformation and analysis:** I Use various data transformation techniques and tools like Excel functions (e.g., vlookup) to categorize and structure the data according to predefined criteria. This includes creating new variables, aggregating data, and conducting exploratory data analysis (EDA) to uncover trends and patterns.

3. **Documentation and reporting:** I document the entire data analysis process, including data sources, cleaning and transformation steps, analysis techniques, and findings. This documentation ensures transparency, reproducibility, and the ability to communicate results effectively to stakeholders.

Overall, my role as a data analyst is instrumental in turning raw data into valuable insights that drive business decisions, improve operational efficiency and enhance customer satisfaction for shop owners and businesses alike.


**SKILLS DEMONSTRATED**


1. **Data sourcing:** Utilizing external sources such as Kaggle and reputable research centers to enhance and contextualize the dataset.

2. **Data transformation:** Employing Excel functions like vlookup to fix missing values

   
**fixing blank cells in Excel:**

A.i. **Identifying blank cells:**
   - Selected blank cells in the dataset.
   - Navigate to the "home" tab.
   - Click on "find and select."
   - Choose "go to special" and select "blank," then click "ok" to select all blank cells.

ii. **Replacing blank cells:**
   - The cell with a white border (active cell) was identified.
   - Typed "=" into the active cell to initiate the formula.
   - The formula automatically fetched the value from the cell above.
   - Pressed "ctrl" and "enter" to replace the formula with the fetched value in the active cell.

iii. **Replacing formulas with values**
   - Select the entire column of filled cells by pressing the "ctrl+shift+down arrow."
   - Copied the selected cells with "ctrl+c."
   - Pasted the copied values back into the same cells using "paste values."

By following these steps, the 35 blank cells in the dataset were efficiently addressed, ensuring data completeness and accuracy for further analysis and visualization.

B. **Creating age brackets with vlookup**
   - Employed the vlookup function to categorize customers into age brackets.
   - Used the formula `=vlookup(c2, age group, d2, 10)` to assign each customer to their respective age group based on predefined criteria.
   - This process streamlined age-based analysis and segmentation, providing valuable insights into customer demographics and behavior patterns.

And employing data manipulation techniques to categorize and structure the data based on predefined criteria.

C. **Data modeling** 
Generating new columns such as "income bracket," "group of spending score," and "age bracket" to enable deeper analysis and segmentation of the customer base.

 Table format for the income bracket and annual income range:

| income bracket | annual income range  |
|----------------|----------------------|
| low income     | $0 - $38,132         |
| middle income  | $38,133 - $114,400   |
| upper income   | $114,401 and above   |




 **PROBLEM-SOLVING AND DECISION SUPPORT**


1. **Income segmentation:** I Analyzed how income levels impact customer behavior and spending tendencies.
2. **Age group analysis:** I Investigate trends and preferences across different age groups to customize marketing strategies and product offerings.
3. **Profession-based insights:**  Exploring the correlation between customers' professions, their spending patterns, and overall engagement with the shop.

This report demonstrates the rigorous data analysis processes employed to extract meaningful insights and guide strategic decision-making for shop owners and businesses alike.


**VIZUALIZATION**

 **Insights generation:** 
Through data visualization and statistical analysis, I extract meaningful insights that help in understanding customer behavior, preferences, and trends. This includes creating charts, graphs, and dashboards to present the data in a clear and actionable format. By leveraging data-driven approaches, I provide actionable recommendations and insights that support strategic decision-making processes. The charts for visualization are all created in **Tableau**


**VIZ 1**

 This area chart of total number of customers for each age bracket with characteristics of age bracket, gender, and total number of customers

![FINANCIAL ANALYSIS  TOTAL No  of customers in each age group](https://github.com/yemifatodu/CUSTOMER-S-FINANCIAL-ANALYSIS-PROJECT/assets/147722919/8042fe99-25d0-495a-b039-fb6ccecb712f)



1. **Key findings:**
   - The total number of customers in each age bracket is depicted, allowing for easy comparison and analysis.
   - The age bracket with the highest number of customers is **81-100**, followed closely by the **31-40** bracket for both **Males** and **Females** respectively. Individually, the lowest bracket for **Females** is **71-80** with a count of **94**, and for **Males**, it is **41-50** with a count of **68**.
   - Gender distribution varies across age brackets, with some brackets showing a more balanced distribution while others skew towards one gender.
   - The total number of customers increases gradually as age brackets increase beyond **80-100**.

2. **Actionable insights:**
   - **Age-based marketing strategies:** Identify the age brackets with the highest concentration of customers and tailor marketing campaigns to target these demographics effectively.
   - **Targeted marketing:** Focus marketing efforts on age brackets with the highest customer count, such as **31-40 and 81-100**, tailoring campaigns based on gender preferences within these brackets.
   - **Customer segmentation:** Consider creating age-specific promotions or products to attract customers in age brackets that show lower engagement, such as those above **71-80**.
 

3. **Future considerations:**
   - **Longitudinal analysis:** Conduct a longitudinal analysis to track changes in customer demographics and preferences over time, identifying emerging trends and opportunities.
   - **Further segmentation:** Explore additional segmentation criteria, such as income levels or geographic location, to deepen understanding and enhance targeted strategies.
   - **Data integration:** Integrate data from other sources, such as purchase history or customer feedback, to enrich analysis and gain deeper insights into customer behavior.

___

**VIZ 2**


![FINANCIAL ANALYSIS  VIZ 2](https://github.com/yemifatodu/CUSTOMER-S-FINANCIAL-ANALYSIS-PROJECT/assets/147722919/1bcda3d6-b93f-4892-83a8-93acfb8b14cc)

1. **Key findings:**
   - The profession with the highest number of customers is the **Artist** for both males and females, with a total count of **622** customers, followed by **Healthcare** with a combined count of **349** customers.
   - Gender distribution within professions varies significantly. For example, in **Artists**, there is **236 Male** customers and **386 Female** customers, indicating a **37.94% Male** to **62.06% Female** ratio. Similarly, in **Healthcare**, the distribution is **149 Male** customers and **200 Female** customers, with a **42.69% Male** to **57.31% Female** ratio.
   - Total customer count varies across professions, ranging from 66 customers in **Homemaking** to **622** customers in professions related to **Artists**.

2. **Actionable insights:**
   - **Targeted marketing strategies:** Tailoring marketing strategies and campaigns based on the gender distribution within each profession and focusing on professions with high customer counts and diverse gender representation.
   - **Product/service customization:** Customizing products or services to cater to the specific needs and preferences of customers in different professions by leveraging insights from gender-specific customer profiles.
   - **Customer relationship management:** More so, implement targeted customer relationship management strategies based on profession-specific customer behaviors and preferences to enhance customer satisfaction and loyalty.

3. **Future considerations:**
   - **Customer segmentation refinement:** Further refining customer segmentation by considering additional factors such as geographic location to gain deeper insights into customer preferences and behaviors.
   - **Customer feedback analysis:** Incorporate customer feedback analysis to understand customer satisfaction levels and identify areas for improvement or innovation within each profession segment.
   - **Competitor analysis:** Conduct competitor analysis within each profession segment to benchmark performance and identify opportunities for differentiation and competitive advantage.
  
___

  **VIZ 3**
This analysis provides a granular understanding of customer demographics and preferences, offering actionable insights for strategic decision-making in marketing, pricing, and customer engagement strategies.

![FINANCIAL ANALYSIS  VIZ 3](https://github.com/yemifatodu/CUSTOMER-S-FINANCIAL-ANALYSIS-PROJECT/assets/147722919/98afaf3b-7744-4928-9ec1-0923bba9c34f)

1. **Key findings:**
- The area chart depicts the distribution of customers, categorized by **Family Size** and **Income Brackets**, using distinct colors to represent each income group. Notable peaks in customer numbers are observed for family sizes **2, 3, and 1**, with a twist in the **Low-income bracket** over family size, where the larger areas in the chart correspond to family sizes **2, 1, and 3**.
- Variations in customer counts are noticeable across different income brackets, such as **Mid-income bracket**, **Upper-income bracket**, and **Low-income bracket**, further illustrating the segmentation within the customer base.

2. **Actionable insights:**
- **Targeted marketing strategies:** Tailoring marketing approaches and product offerings should be based on prevalent family sizes and income brackets to effectively reach larger customer segments.
- **Pricing and promotions:** Adapting pricing strategies and promotional campaigns according to the income distribution within each family size group can optimize revenue generation.
- **Customer segmentation:** Utilizing insights derived from the chart can facilitate more refined customer segmentation based on both family size and income levels, facilitating personalized marketing strategies and service delivery.

3. **Future considerations:**
- **Customer behavior exploration:** Delving deeper into customer behaviors and preferences within specific family size and income bracket segments can unveil trends and opportunities for enhancing customer engagement.
- **Market expansion initiatives:** Identifying and targeting underrepresented customer segments, particularly in terms of family size and income brackets, presents opportunities for expanding market reach through strategic marketing endeavors.

___

**VIZ 4** 
**Visualization of customer count by income bracket with gender details**

The area chart analysis delves into customer distribution across various professions, segmented by income brackets and accompanied by a breakdown of gender representation within each profession group.


![FINANCIAL ANALYSIS  VIZ 4](https://github.com/yemifatodu/CUSTOMER-S-FINANCIAL-ANALYSIS-PROJECT/assets/147722919/90d035b1-e0cb-4b4a-b881-8ad49e50a8e0)

In the analysis, the area chart visually showcases the number of customers in each profession, providing a clear picture of how this varies across different income brackets. In addition, the use of color coding reveals the gender distribution within each profession category, offering insights into the overall gender composition of customers across income levels.


**Key findings**

- The visualization presents the count of customers for each income bracket, with color indicating details about gender.
- Each bar represents the count of customers within a specific income bracket. For example, in the **Low-income bracket**, there are **108** customers; in the **Mid-income bracket**, there are **951** customers; and in the **Upper-income bracket**, there are **941** customers.
- Gender details are shown within each income bracket. For instance, in the **Low-income bracket**, there are **47 Male** customers and **61 Female** customers, while in the **Mid-income bracket**, there are **389 Male** customers and **562 Female** customers, and in the **Upper-income bracket**, there are **378 Male** customers and **563 Female** customers.


**Actionable insights:**
- **Gender-based targeting:** Tailoring marketing strategies to align with the gender distribution within each profession segment can enhance customer engagement and retention.
- **Income-driven product development:** Adapting products or services to suit the unique needs and preferences of customers in different income brackets, informed by gender-specific customer profiles, can boost satisfaction and loyalty.
- **Profiling high-value customers:** Identifying high-value customer segments within professions and income brackets allows for personalized approaches in engagement and retention efforts.

**Future considerations:**
- **Customer lifetime value analysis:** Delving deeper into customer lifetime value within specific profession and income bracket segments aids in prioritizing resource allocation and refining customer relationship management strategies.
- **Market expansion opportunities:** Exploring growth avenues within professions and income brackets showing potential can inform targeted expansion initiatives based on gender-specific customer demographics and preferences.
- **Competitive benchmarking:** Comparing customer counts and gender distributions with competitors provides valuable insights for enhancing customer acquisition and retention strategies.

This comprehensive analysis offers detailed insights into customer demographics, spending behaviors, and gender-specific preferences, providing a solid foundation for informed decision-making in marketing, product development, and customer engagement endeavors.

___


**VIZ 5: Bar chart analysis - Distribution of annual income among different professions**

![FINANCIAL ANALYSIS  VIZ 5](https://github.com/yemifatodu/CUSTOMER-S-FINANCIAL-ANALYSIS-PROJECT/assets/147722919/e86f08db-4903-4b81-921c-4f6e81959b9b)

**Key findings**
1. **Visual representation:** The bar chart visually represents the distribution of annual income across various professions.
2. **Income diversity:** The table shows the income range for each profession, highlighting the variability in income levels across different job roles. Color coding in the bar chart further emphasizes these income distribution patterns, showcasing concentrations of certain income levels within specific professions.

| profession   | income range                      |
|--------------|-----------------------------------|
| Artist       | $2,000 to $189,709               |
| Doctors      | $3,000 to $189,672               |
| Engineer     | $7,000 to $189,974               |
| Entertainer  | $1,000 to $186,882               |
| Executives   | $4,000 to $189,630               |
| Healthcare   | $3,000 to $189,369               |
| Homemaker    | $29,000 to $188,696              |
| Lawyer       | $3,000 to $189,650               |
| Marketing    | $5,000 to $186,069               |



**Actionable insights**
- **Income segmentation strategy:** Tailor marketing strategies and promotions to target customers within different income brackets and professions, focusing on attracting and retaining high-value customers.
- **Pricing optimization:** Adjust pricing strategies based on income distribution among professions to ensure affordability and value perception for customers, optimizing revenue generation.
- **Targeted product offerings:** Introduce customized products or services targeting specific income segments within professions, aligning offerings with customer purchasing power and preferences.

**Considerations for future analysis:**
- **Market trend analysis:** Monitor income distribution trends over time to identify emerging patterns and opportunities for market expansion or diversification.
- **Customer satisfaction surveys:** Gather feedback from customers across various income brackets and professions to gauge satisfaction levels and tailor offerings accordingly, enhancing customer experience.
- **Competitive benchmarking:** Compare income distribution among professions with competitors to benchmark performance, identify areas for differentiation, and leverage competitive advantages.

___

**VIZ 6b: Bar chart analysis - Income distribution across different age groups (binned)**

![FINANCIAL ANALYSIS  VIZ 6](https://github.com/yemifatodu/CUSTOMER-S-FINANCIAL-ANALYSIS-PROJECT/assets/147722919/bf2e413a-7093-4e92-8096-4ec47fc31d57)

**Key findings**
- The bar chart visually depicts income distribution across different age groups using binning techniques. Each bar represents income distribution within a specific age group bin. For example, individuals in the **Age group of 6, 84, and 96** have about **50%** of the total **Annual Income**.
- The chart reveals varying income levels among age groups, with concentrations of individuals in specific income brackets reflecting income diversity across different age cohorts.

**Actionable insights**
1. **Age-specific marketing strategies:** Develop targeted marketing campaigns and promotions tailored to the income levels, preferences, and purchasing behaviors of different age groups.
2. **Product customization:** Customize products or services to meet the specific needs and affordability of customers within each age group, ensuring relevance and value.
3. **Financial planning services:** Offer financial planning or investment options aimed at age groups with higher income levels, addressing their financial goals.

**Future considerations**
1. **Longitudinal income analysis:** Analyze income trends over time across age groups to predict future distributions and plan strategic initiatives effectively.
2. **Customer lifetime value assessment:** Evaluate the lifetime value of customers within different age segments based on their income, guiding resource allocation and relationship management strategies.
3. **Market segmentation refinement:** Refine market segmentation by integrating income distributions with other demographic factors like gender, profession, or location for a more comprehensive understanding.

___

**VIZ  7: Bar chart analysis - Income distribution across various professions**

This bar chart involves analyzing the specific income ranges for each profession category within the bar chart.

![FINANCIAL ANALYSIS  VIZ 7](https://github.com/yemifatodu/CUSTOMER-S-FINANCIAL-ANALYSIS-PROJECT/assets/147722919/0019adda-d963-4e1b-9f07-8a34a55f4c65)

**Key findings:**
- The bar chart presents the distribution of income across different professions.
- Color coding is used to indicate income brackets within each profession category, offering a visual representation of income distribution patterns.
- Professions such as **Artists, Healthcare, and Entertainment** exhibit varying income levels, with some professions having higher concentrations in certain income brackets.

**Actionable insights:**
- **Professions' income profiles:** Understand the income profiles of different professions to tailor products, services, and marketing strategies accordingly.
- **Targeted offerings:** Develop targeted offerings and promotions based on income brackets within each profession, catering to diverse customer segments effectively.
- **Income-based customer segmentation:** Segment customers based on their professions and income levels for personalized engagement and relationship-building initiatives.

**Future considerations:**
- **Income growth opportunities:** Identify professions with potential income growth opportunities to focus on capturing new customer segments or expanding the existing customer base.
- **Competitive benchmarking:** Compare income distributions across professions with industry benchmarks to assess market competitiveness and strategic positioning.
- **Customer lifetime value analysis:** Analyze the lifetime value of customers within different income brackets and professions to prioritize resource allocation and customer retention efforts.

___

**VIZ 8: Bar chart analysis - Spending score analysis based on different family sizes**
This analysis involves calculating and presenting the specific spending scores for each family size category within the bar chart.
![FINANCIAL ANALYSIS  VIZ 8](https://github.com/yemifatodu/CUSTOMER-S-FINANCIAL-ANALYSIS-PROJECT/assets/147722919/66e5b443-8483-40b3-8424-989758695caa)

**Key findings:**
- Color coding is used to represent details related to family size within the spending score analysis, providing a visual understanding of spending behavior across family size categories.
- Family sizes exhibit varying spending score distributions, highlighting potential patterns and trends.

**Actionable insights:**
- **Family size spending patterns:** Analyze spending patterns across different family sizes to identify potential opportunities for targeted marketing and product offerings.
- **Customer segmentation:** Segment customers based on family size and spending behavior to create personalized promotions and loyalty programs.
- **Resource allocation:** Allocate resources effectively by understanding spending preferences and behaviors associated with different family sizes.

**Future considerations:**
- **Trend analysis:** Conduct trend analysis over time to track changes in spending behavior across various family sizes and adapt strategies accordingly.
- **Customer engagement strategies:** Develop engagement strategies tailored to different family sizes, considering their unique spending preferences and needs.
- **Market expansion opportunities:** Explore opportunities for market expansion or diversification based on spending score analysis and family size segmentation.
  
 This analysis can provide valuable insights into spending behavior across different family sizes, guiding targeted marketing campaigns and customer segmentation strategies.
___

**VIZ 9: Bar chart - Unique count of spending scores by age groups (bin)**
 The bar chart visually represents the unique count of spending scores categorized by age groups (bin), providing insights into spending behaviors across different age segments.
 
 ![FINANCIAL ANALYSIS  VIZ 9](https://github.com/yemifatodu/CUSTOMER-S-FINANCIAL-ANALYSIS-PROJECT/assets/147722919/d8ad4184-a7d2-40e5-9355-a52d8e3233d6)

**Key Findings**

- Each bar signifies the distinct count of spending scores within a specific age group bin. For example, in **Age 90, Age 30, and Age 24**, there are **75 unique spending scores**, with **Age 96 having the lowest unique count of spending scores at 49**.

**Actionable insights:**
- Unveiling age-based spending patterns: Delve into spending patterns across age groups to tailor marketing strategies and promotions specifically targeting different age demographics.
- Crafting engaging customer strategies: Formulate engagement strategies and loyalty programs based on observed spending behaviors within various age brackets.
- Capitalizing on product development opportunities: Recognize product or service offerings that align with the spending preferences of different age groups to enhance overall customer satisfaction.

**Future considerations:**
- Longitudinal spending analysis: Conduct longitudinal analysis to track spending behavior changes within age groups over time, adapting strategies accordingly for sustained effectiveness.
- Evaluating customer lifetime value: Assess the lifetime value of customers within distinct age segments based on their spending scores, prioritizing efforts for customer retention.
- Fine-tuning market segmentation: Refine market segmentation strategies using insights from spending score analysis and age group demographics for more targeted marketing initiatives.

---

**VIZ 10: Bar chart - Spending score analysis for each income bracket**

![FINANCIAL ANALYSIS  VIZ 10](https://github.com/yemifatodu/CUSTOMER-S-FINANCIAL-ANALYSIS-PROJECT/assets/147722919/a3056129-5dc4-47c1-8a23-3bb060c98910)

**Key findings:**
- The bar chart depicts the spending score analysis for each income bracket, utilizing color to delineate details related to income brackets.
- Each bar showcases the spending scores within a specific **Income bracket**. For example, in **Low income**, there are **99 spending scores**, in **Mid income**, there are **100 spending scores**, and in **Upper-income,** there are **100 spending scores**.
- Income brackets such as low income, middle income, and upper income showcase distinct spending patterns, with low income having a lower spending score.

**Actionable insights:**
- Crafting income-driven marketing strategies: Tailor marketing strategies and promotions for different income brackets to optimize customer acquisition and retention efforts.
- Strategic pricing and offerings: Adjust pricing strategies and product offerings based on observed spending behaviors within each income bracket to enhance the overall value proposition.
- Segmenting customers for enhanced personalization: Refine customer segmentation based on income brackets to create targeted campaigns and personalized experiences catering to diverse customer segments.

**Future considerations:**
- Conducting price sensitivity analysis: Dive into price sensitivity within income brackets to gauge customers' willingness to pay and refine pricing strategies accordingly.
- Maximizing customer lifetime value: Focus on maximizing the lifetime value of customers within higher income brackets through tailored loyalty programs and premium offerings.
- Exploring market expansion avenues: Explore opportunities for market expansion based on spending score analysis and income bracket segmentation to tap into new customer segments effectively.
___

**CONCLUSION:**


In conclusion, the shop customer data analysis project has provided valuable insights into the characteristics and behaviors of an imaginary shop's customer base. Through rigorous data analysis and visualization techniques, we have uncovered patterns and trends that can significantly impact business strategies and customer engagement efforts.

the analysis revealed key findings such as:
- the distribution of customers across different age groups and professions, providing insights into demographic preferences and market segments.
- the relationship between income levels and spending behavior, highlighting the importance of tailored marketing strategies based on income brackets.
- the impact of family size on spending patterns, offering opportunities for targeted promotions and product offerings.



**RECOMMENDATIONS**

Key findings such as the distribution of customers across different age groups and professions, the relationship between income levels and spending behavior, and the impact of family size on spending patterns have been highlighted. Based on these findings, here are some recommendations:

1. **Personalized marketing strategies:** Develop personalized marketing strategies targeting specific age groups, professions, and income brackets to enhance customer engagement and loyalty.
2. **Product offerings:** Tailor product offerings and promotions based on customer demographics and spending behaviors to optimize sales and customer satisfaction.
3. **Customer segmentation:** Refine customer segmentation strategies based on age, income, and family size to create targeted campaigns and improve customer acquisition.
4. **Data-driven decision-making:** Emphasize the use of data-driven decision-making processes across departments, leveraging insights from analytics tools to drive business growth and profitability.
5. **Continuous analysis:** Conduct regular analysis and monitoring of customer data to identify evolving trends, preferences, and market opportunities for proactive business strategies.

**Dashboard Preview**

![Dashboard 2 pngCUSTOMER F](https://github.com/yemifatodu/CUSTOMER-S-FINANCIAL-ANALYSIS-PROJECT/assets/147722919/438fdd57-cf44-42da-bd3f-311694c5f4af)

**Dashboard link**
[Link to Dashboard here](https://public.tableau.com/views/CUSTOMERFINANCIALANALYSIS/Dashboard2?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link&:device=desktop)
BETTER VIEW IN DESKTOP VERSION

**Dataset Link**
[Link to the dataset](https://1drv.ms/x/c/7256ba81ae14a105/EbqiL2k-J_hEnWsf9l_EmEIBvXRncAwG_GOxCT6wI-U9iQ)

This link directs users to the dataset used in the analysis, allowing for transparency and reproducibility of the findings presented in the report.

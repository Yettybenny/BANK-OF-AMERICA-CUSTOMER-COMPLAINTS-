# BANK-OF-AMERICA-CUSTOMER-COMPLAINTS-

## Introduction

In today’s competitive financial landscape, understanding and addressing customer complaints is essential for improving satisfaction and loyalty. In this project, I analyzed Bank of America’s customer complaint data to identify patterns, trends, and potential areas for improvement. Using Power BI, I developed an interactive dashboard that presents a clear overview of the complaints, with insights to help reduce recurring issues.

## Objectives 

The main goal of this project was to:

- Analyze the customer complaint data to uncover trends.

- Identify patterns in complaints based on product, location, and time.

- Provide data-driven recommendations to help Bank of America address customer concerns more effectively.

### Dataset Overview 

The dataset used in this analysis contained customer complaints reported to Bank of America. Key columns included:

- Complaint ID: A unique identifier for each complaint.

- Product: Type of banking product involved in the complaint (e.g., credit card, mortgage).

- Issue: Specific issue raised by the customer.

- Sub-Issue: Further detail on the issue (some values were missing here).

- State: The location of the customer filing the complaint.

- Submitted Via: The channel through which the complaint was submitted (e.g., Web, Phone).

- Date Received: The date the complaint was received.

- Timely Response: Whether the bank responded in a timely manner.

- Response Status: Status indicating if the response was satisfactory, not given, or pending.


### Data Cleaning

To ensure accuracy, I conducted data cleaning steps in Power Query. This process included:

- Since the "Sub-Issue" column had several missing values, I decided to retain these rows to preserve valuable information about the main "Issue." The lack of sub-issue details was noted as a limitation.

- I converted state abbreviations to full names for readability, which involved using a lookup table for consistency.

- I checked for any duplicate complaints by comparing Complaint IDs and removed any unnecessary duplicates to ensure data integrity.

## Exploratory Data Analysis

Once the data was cleaned, I explored it using various Power BI visualizations:

- Complaints by Year: A bar chart displayed the trend in complaint volumes over the years, helping identify any significant increase or decrease.

- Complaints by Product: Another bar chart highlighted which products received the most complaints. This was useful in pinpointing areas requiring immediate attention.

- Complaints by Media: A bar chart showed the preferred channels for submitting complaints, with "Web" being the dominant method.

- Timely Response Rate: A donut chart illustrated how many complaints received timely responses.

- Complaints by State: A map visualization highlighted the distribution of complaints across states, allowing for geographic insights.


### Dashboard Design

-Design Choices

The dashboard was designed to be intuitive and user-friendly. Key design choices included:

- A professional dark background with Bank of America’s red and white accents to align with branding and improve readability.

-Filters for Year, Product, State, and Issue allow users to explore the data based on specific criteria.

## Key Insights

Key insights gained from the data:

- There has been a noticeable peak in complaints around 2022 with 13K complaints, followed by a slight decline in subsequent years (9K in 2023). This trend might indicate that some issues were addressed, but ongoing monitoring is essential.

- The “Checking account” and “Credit card” categories have the highest complaints, with 25K and 16K respectively. These products could be causing significant issues for customers.

- “Unexpected fees,” “Trouble when making payments,” and “Fraud/Scam” are among the most reported issues. Addressing these common pain points could improve customer satisfaction significantly.

- The majority of complaints (93.77%) received a timely response. However, 3.84% of cases were not given timely responses, indicating a need to improve response rates further. California is highlighted as the state with the highest complaints. Other high-complaint states include Texas and Florida.

- Most complaints were received via the “Web” channel (45K), while other channels like “Phone” and “Referral” have much lower complaint counts. This insight suggests that digital channels are the primary mode of customer interaction and complaint filing.

- The trend of complaints per month does not show a consistent pattern, which might indicate seasonal or operational fluctuations.

## Limitations

Some limitations of this analysis include:

- Some details, especially in Sub-Issue and Public Response, are missing.

- We don’t know if customers are happy after their issues are resolved.

- The dataset does not include information on customer satisfaction following complaint resolutions. This limitation restricts the ability to fully understand the impact of responses on customer loyalty and satisfaction, which are crucial for assessing the effectiveness of complaint resolution strategies.

- Since most complaints were filed online, there may be underrepresentation from other channels, such as in-person visits or phone calls, which could provide a different perspective.

## Recommendations

Based on the analysis, here are some recommendations Bank of America could consider:

- Since “Checking account” and “Credit card” have the highest complaints, Bank of America should investigate these areas. Offering clearer terms, improved customer support, or fee reductions might help reduce issues.

- Focus should be on resolving the top issues, unexpected fees, payment troubles, and fraud/scams. Introducing transparent fee structures, strengthening security protocols, and streamlining payment processes can reduce complaints.

- Although most complaints receive timely responses, there’s room for improvement. Bank of America could consider implementing automated responses to acknowledge complaints immediately, followed by a structured escalation for more complex cases.

- Since a significant number of complaints are received via the web, providing more self-help resources on the website or enhancing FAQ sections might reduce complaint numbers by empowering customers to solve common issues independently.

- States like California, Texas, and Florida should be prioritized for targeted interventions. Additional customer service resources or specific campaigns in these regions may help reduce complaint volumes.

- The monthly complaint trend shows varying volumes. It may be helpful for the customer support team to have flexible staffing during higher complaint months or to use predictive analytics to anticipate peak periods.

## Conclusion

This project highlights the importance of data-driven insights for customer experience improvements in the financial industry. By identifying complaint trends and analyzing them in Power BI, I provided actionable insights for Bank of America to enhance its customer service and address common issues. This dashboard can serve as a tool for regular monitoring and improvement, helping the bank reduce complaints over time and build stronger customer relationships.



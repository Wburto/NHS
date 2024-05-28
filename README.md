# NHS: Utilisation & Capacity Analysis- 89% final grade.

### Project Summary: 
The second LSE six week fictional project involved the NHS. The project was aimed at addressing the abstract issues of adequate capacity and utilisation within the system by considering appointment data. Through rigorous data analysis I identified key areas for improvement: optimising resource allocation, forecasting health trends, and improving patient care services.

The report considered the two primary business questions as proposed by the NHS:

- Has there been adequate staff and capacity in the networks?
- What was the actual utilisation of resources?

### Analytical Approach Highlights:
- **Data Consolidation and Integrity:** I focused on data quality and standardisation issues of which there were many. I used the metadata to identify and correct data issues, specifically noting that the data was not originally designed for analysis. In spite of this, I demonstrated proficiency in consolidating data sets. When possible, ensuring accuracy and reliability analysis outcomes.
- **TimeSeries for Predictive Forecasting:** I Illustrated proficiency through TimeSeries analysis, utilising Python for forecasting. This proved essential for predicting trends and making data-driven decisions, showcasing my ability to handle and analyse time based data effectively.
- **Research:** I conducted thorough research, integrating findings from a wide range of sources including 44 references from several reliable sources. This ensured a well-rounded analysis, grounded in evidence and diverse perspectives.
- **Targeted insights**: I demonstrated the ability to translate complex data into actionable insights justified by strong research, focusing on strategic recommendations based on data analysis. Highlighting a results-oriented approach to an otherwise nebulous business question.

### **Key Insights and Recommendations:**

- I revealed 65% average utilisation rate during a long data period that included Covid, identifying potential underutilisation and capacity expansion opportunities.
  - A timeseries plot looking at utilisation of NHS services across the data time period against real world events.
  - ![image](https://github.com/Wburto/NHS/assets/132344378/c4663bc2-da33-4d6a-8e1b-60c13dec8517)

- I raised data concerns by addressing metadata and data quality issues, which ultimately affected 13% of appointments, equating to approximately 38,971,612 appointments with data inconsistencies.
  
- I utilised Python for data manipulation and visualisation, creating over 20 graphs to provide insights on the business questions.
  
- I identified regional discrepancies in NHS appointment allocations, directly correlating to population representation, leading to potential future location based recommendations for resource reallocation.
  - The box plot shows us just how many appointment counts like outside the IQR and the regional discrepancies. 
  - ![image](https://github.com/Wburto/NHS/assets/132344378/1b194f54-d9fb-40e7-b9de-a999bdaa415d)


- I created simple, bespoke sentiment analysis tool for use on Twitter data, filtering through keywords and hashtags to evaluate public sentiment, identifying opportunities for service improvement and potential future usage. I also noted the problems with the Twitter data provided and suggested actionable improvements to their data gathering process.
  
- I developed strategic recommendations to potentially increase NHS appointment availability through optimising thoroughly researched appointment delivery methods. This included recommending that GP’s use the more efficient telephone appointment rather than face-to-face and that “other practice staff” increase appointment workload to free up more GP time. Currently GPs handle 51% of appointments, while Other Practice Staff manage 46%.
  - Appointment mode trends over time shows us the driving force of face to face and how underutilised the other modes are by comparison. 
  - ![image](https://github.com/Wburto/NHS/assets/132344378/19d175fd-33eb-4ae9-a7bc-584f095e62b5)


- I noted missed appointment costs of approximately £927 million from January 2020 to June 2022, underscoring the financial impact of data quality and patient attendance.
  - ![image](https://github.com/Wburto/NHS/assets/132344378/e5fb9db4-a6f3-433b-94fd-8222e13ad89f)
  - In 2019 a report on the cost of missing appointments calculated the following:
  - “Each appointment costs an average of £30, putting the total cost to the NHS at more than £216 million pounds on top of the disruption for staff and fellow patients that would pay for:
      - The annual salary of 2,325 full time GPs
      - 224, 640 cataract operations
      - 58,320 hip replacement operations
      - 216,000 drug treatment courses for Alzheimer’s
      - The annual salary of 8, 424 full time community nurses”. (NHS. (2019) 20)
  - If we apply that £30 missed appointment metric to our data, then 30,911,233 not attended appointments over the 18 months period that the
dataset covers costs the NHS £ 927,336,990

- I noted appointment duration efficiency issues using the previously government suggested metric of “under 14 days” for the target time before book and appointment. This showed us that 88% of appointments do reach that target. However the 12% that don’t equal 91 million appointments.
  - A huge amount of data issues are highlighted here as well as the large spread of appointment durations. 
  - ![image](https://github.com/Wburto/NHS/assets/132344378/d2606b04-33e9-43b7-8681-1f2ec63f41b7)



### Professional Development and Impact: 
This project underscored my proficiency in leveraging advanced analytics, research, and data visualisation techniques to drive significant potential improvements for the NHS. The initiative not only showcased my technical acumen but also highlighted my ability to translate data insights into actionable strategies that enhance service delivery and operational efficiency.

Presentation: https://youtu.be/_tA6TNtepQA?feature=shared 

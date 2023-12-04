# RetroPGF3List_Methodology
Here you'll find some of the methodology for my lists.

## Numba NERDs
Data sources here: [Application Data](https://app.dework.xyz/optimism-community/main-space-35638/view/board-l8x6w840)

| **Criteria** | **Description** | **Metrics for Evaluation** | **Specific Insights/Metrics** | **Rating Scale (1-5)** | **Allocation** | **Calculation** |
|--------------|-----------------|----------------------------|-------------------------------|------------------------|----------------|-----------------|
| **1. Creation of Deep Dive Analysis** | Assess the quantity and quality of deep dive analyses created by the team. | Count the number of deep dive analyses produced. Evaluate the comprehensiveness and depth of each analysis. | 13 deep dives completed: 5 robust, 8 less robust. | 3 | $5,000 per robust analysis, $2,500 for less robust ones | $25,000 for robust (5 x $5,000) + $20,000 for less robust (8 x $2,500) = $45,000 |
| **2. Utilization in Discussions** | Measure how often the team's analyses are referenced or used in discussions (removing specific focus on forums). | Track mentions and references of the team’s analyses in discussions. | Synthetix linked 4 times; Polynomial linked 5 times; Via Protocol mentioned 2 times; Celer referenced 3 times. The overall consumption of the deep dives is limited. | 3 | $10,000 per rating point | $30,000 (3 x $10,000) |
| **3. Impact on Decision Making** | Evaluate the influence of the team's analysis on decision-making processes within the Optimism ecosystem. | Assess instances where the team's analysis directly influenced decisions or policy changes. | Synthetix analysis significantly influenced the grants program. Polynomial analysis received substantial feedback and led to actionable changes. | 4 | $10,000 per rating point | $40,000 (4 x $10,000) |
| **4. Recommendations to Ecosystem Partners** | Assess the effectiveness and relevance of the team's recommendations to ecosystem partners. | Evaluate the clarity, feasibility, and alignment of recommendations with partners' goals. | Varied effectiveness: Kwenta received great feedback, while recommendations for Thales and Via Protocol were more basic. | 3 | $10,000 per rating point | $30,000 (3 x $10,000) |
| **5. Governance Data Accessibility** | Assess how effectively the team makes governance data accessible and understandable. | Evaluate the creation of spells in Dune (considering complexity), the presence of reports in governance forums, and the provision of simplified takeaways. | 10 small spells; 1 large spell; 1 large spell with less impact; 2 bi-weekly OPMainnet updates. | 4 | OP amounts: Small spells $200 each, Large spells vary ($4k and $2k), Bi-weekly OPMainnet updates $1,500 each. | $2,000 (10 small spells x $200) + $4,000 + $2,000 + $3,000 (2 updates x $1,500) = $11,000 |
| **Total** | - | - | - | - | **Sum of Allocations** | **$156,000** |



## Optimism Translators:
Data can be found here: [Application Data](https://docs.google.com/spreadsheets/d/1hVWSrZKrt3Cp7cC5ZFX10-E1KSR4s_58Zg_iCjgt85c/edit#gid=0)

1. **Calculated the average number of words per article included in the RetroPGF application.**
2. **Calculated the total number of words translated per language, per type of contribution (Mirror articles vs official (technical) documentation).**
   ### For Articles:
   - **i.** Categorized the "translated into" languages into 4 groups based on their translation pair "rarity" (how uncommon they are in the translation market).
   - **ii.** Categorized the "translated into" languages into 5 groups based on the size of the languages' speaking population (1 most spoken - 5 least spoken).
   - **iii.** Multiplied the number of translated words per language by 0.2 to get the OP amount per language.
   - **iv.** Multiplied the OP amount per language times the rarity level as a percentage (1% most common, 4% rarest pairs).
   - **v.** Multiplied the result of iv) by their speaking population group with the logic (0% for least spoken, 10% for most spoken). (I think this is fine because this is where community-tailored content shines.)
   - **vi.** Summed all OP amounts per language.
   ### For Optimism Help Center:
   - **i.** Multiplied each translated word by 0.25(OP) (higher amount based on technical docs).
   - **ii.** Multiplied only approved words by 0.15(OP) (smaller amount since it's QA).
   - **iii.** Added a bonus of 2K OP per 99-100% translated language in Crowdin (to signal the importance of fully translated languages).
   - **iv.** Added a bonus of 1K OP per language with over 50% of content translated.
   - **v.** Sum all amounts from i) to iii).

**Final amount:** Add Help Center OP amounts and Article OP amount, round up to the closest 1k.

    
Python script under "Optimism translators" doc


## TechNERDs
| **Criteria** | **Objective** | **Metrics / Evaluation Points** | **Allocation Methodology** | **Final Scoring** |
|--------------|---------------|---------------------------------|----------------------------|-------------------|
| Time Saved for Core Developers | Measure the extent to which the tech support program has freed up core developers' time. | - Estimated hours saved per week/month for core developers.<br> - Qualitative feedback from core developers. | 50 OP per closed thread | $8,800 |
| Response Time Efficiency | Assess how the program has reduced waiting times for developer queries. | - Average response time before and after the implementation of the tech support program.<br> - Percentage reduction in waiting time. | 10 OP if marked as Fast Response by user | $560 |
| Support Ticket Resolution | Evaluate the effectiveness in handling and resolving support tickets. | - Total number of closed support tickets.<br> - Average time taken to close a ticket.<br> - Breakdown of ticket types and resolution rates. | 2k OP for every 100% KPI exceeded | $4,400 |
| User Support Rating | Gauge user satisfaction with the support provided. | - Average user support rating on a scale.<br> - Distribution of ratings and analysis of any low ratings. | 1k OP per Support nerd that achieves a rating of over 4.5 in their interactions | $4,000 |
| Community Engagement and Growth | Assess the program's impact on community engagement and ecosystem growth. | - Increase in active community members.<br> - Contributions to community forums and discussions.<br> - Engagement in community events or hackathons. | Rated in a 1 to 5 scale, with each rating increasing by 2k OP | $6,000 |
| Innovation and Developer Experience Enhancement | Evaluate contributions to innovation and improvements in the developer experience. | - New tools or methods introduced.<br> - Feedback from developers on improvements in their workflow or problem-solving efficiency.<br> - Adoption of new practices within the community. | 50 OP per PR opened<br>150 OP per PR merged<br>50 OP per issue created | $2,750 |
| Overall Contribution to Ecosystem Health | Measure the overall impact on the health and progress of the Optimism Ecosystem. | - Long-term effects on ecosystem stability and growth.<br> - Contributions to key ecosystem projects or initiatives.<br> - Recognition within the ecosystem (awards, mentions, etc.). | Cannot be measured yet, but with the data collected for this round hopefully we can create a long-term view of the impact. |  |
| Subjective criteria | Sustainability focused | - Their current grant for the worked time is locked for a year, suggest adding and additional half through RetroPGF so they can use it.<br> - Measurement of hard data and indicators that will help them improve them program in the long run has been done for this round |  | $13,400 |
| **Total to be rewarded** |  |  |  | **$39,910** |

Rounded up to the closest 1k when allocating. 

Data and calculations can be found here: [Application Data](https://docs.google.com/spreadsheets/d/1-4y-1KAjFUF602Oi7ty40BCRHJRLpNj_0NNIbNT9gP0/edit?usp=sharing) and here: [Ticket data](https://docs.google.com/spreadsheets/d/18Wt5X_CM8BXC7UM7Cw8sCcZ789K6zeOWjIZvSPWf0eM/edit#gid=1570985542)


## SupNERDs

Data sources here: [Application Data](https://docs.google.com/spreadsheets/d/1JfERz7nMpVnl0J8Ea-pqD6gmXe4CZlH7u7PTGEzqPGA/edit#gid=1131397769)

Step 1. Calculate number of hours worked and reward just based on number of hours. 
1. **Total Number of Messages Sent**: 47,088 messages.
2. **Average Messages Sent per Hour**: 18 messages/hour (based on industry standards).

Total Hours Worked = Total Number of Messages / Average Messages Sent per Hour
                   = 47,088 messages / 18 messages/hour
                   ≈ 2616 hours.

Now, multiplying this by 22:
2616 hours × 22 ≈ 57,552 USD. Turning into OP on a 1.3 valuation = $44,270.77

| **No.**   | **Criteria**                                    | **Measurement**                                                 | **Rating Levels**                                                                                                                                                                                                                     | **Project Evaluation**                                            | **Amount Awarded** |
|-----------|-------------------------------------------------|-----------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------|--------------------|
| 1         | Support and Safety in the Discovery Journey     | Number of resolved support queries, time taken to resolve queries | High: High resolution rate with quick response times. Medium: Moderate resolution rate with average response times. Low: Low resolution rate, slow response times.              | **High:** 94% of 1819 support queries closed.                      | $15,000           |
| 2         | User Experience                                 | Average user support rating, frequency and quality of user feedback | High: High average user support rating, frequent positive feedback. Medium: Moderate ratings and mixed feedback. Low: Low ratings, negative feedback.                        | **High:** Average user rating of 4.5; outstanding feedback.        | $20,000           |
| 3         | Adoption and Participation                      | Active user engagement metrics, participation rates in community events or forums | High: Strong active user engagement, high participation in events/forums. Medium: Moderate user engagement, average participation. Low: Low user engagement, minimal participation. | **Medium:** 10 out of 40 participants actively engaged.             | $10,000           |
| 4         | Accessibility and Language Support              | Availability and quality of multilingual support services, user feedback on effectiveness of language support, turnaround time for multilingual support requests | High: Wide availability and high quality of multilingual support services, excellent user feedback, quick turnaround for support requests. Medium: Moderate availability and quality of support services, mixed user feedback, average turnaround time. Low: Limited availability and poor quality of support services, negative user feedback, slow turnaround time. | **High:** Extensive range of languages supported, indicating strong emphasis on multilingual accessibility. | $30,000           |
| **Total Amount Based on Criteria** |                     |                                                                 |                                                                                                                                                                              |                                                                    | **$75,000**         |
| **Worked Hours** |              |                                                                 |                                                                                                                                                                              |                                                                    | $44,270.77         |
| **Grand Total**  |                                             |                                                                 |                                                                                                                                                                              |                                                                    | **$119,270.77**    |

Round up to the closest 1K when allocating. 

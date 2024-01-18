Hypothesis:
My hypothesis was that there would be a significant increase in screen time, particularly in social media and entertainment categories, during the evening hours compared to other times of the day.

Imported Libraries: I began my analysis by importing essential Python libraries, namely Pandas for data handling and analysis, and Matplotlib and Seaborn for visualization purposes.

Defined a Time Conversion Function: To facilitate the analysis, I created a function, time_to_minutes, to convert time recorded in hours and minutes into total minutes. This conversion was crucial for quantitative analysis.

Prepared the Data: I organized my screen time data into a dictionary called weekday_data, where each day was broken down into different time blocks, each containing usage times for various app categories.

Converted and Aggregated Data: Utilizing my time_to_minutes function, I transformed the screen time data into minutes and compiled it into a pandas DataFrame for further analysis.

Computed Descriptive Statistics: I then calculated basic descriptive statistics for the DataFrame to get a broad understanding of my screen time distribution.

Analyzed Average Screen Time: I calculated the average screen time for each category across days to identify any notable usage patterns.

Visualized Total Social Media Usage: I used a line graph to depict my daily social media usage, helping me to spot any significant trends throughout the week.

Performed Comparative Category Analysis: To understand my usage patterns, I calculated and visualized the total screen time for each category, which highlighted which categories were used most.

Focused on Evening Usage Analysis: In line with my hypothesis, I specifically analyzed screen time in the social and entertainment categories between '12:00-18:00' and '18:00-24:00'.

Calculated Percentage Increase: Lastly, I calculated the percentage increase in screen time during the evening hours compared to earlier in the day to quantify the change and assess my hypothesis.

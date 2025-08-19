📢 Project: YouTube Channel Performance Tracker (Personal Project) 📊
Tools Used: Power BI, DAX, Google Sheets, CSV Data, Data Modeling 💡 
✅ Project Overview 💡 
I built an interactive Power BI dashboard to analyze YouTube channel performance over multiple years, focusing on audience engagement, category performance, and growth trends.
 The goal was to identify which content works best and how to optimize posting schedules for better results.
✅ Data Transformation
I worked with two datasets:
Video Metadata: Video ID, Title, Category, Upload Date, Duration, etc.
Video Performance: Views, Likes, Comments, Subscribers Gained, Watch Time, etc.
💡 Steps I performed:
✅ Data Cleaning
Removed duplicates and invalid rows
Standardized category names (e.g., “tutorial” → “Tutorial”)
Converted UploadDate to proper date format
Filled missing numeric values with 0 for metrics like Likes or Comments
✅ Data Formatting
Created calculated columns:
DayOfWeek to identify posting day
UploadPeriod (Midweek / Weekend)
MonthYear for monthly trend analysis
Changed column data types for correct aggregation (Views → Whole Number, Dates → Date)
💡 💹 Data Modeling
Built a star schema with Video Metadata as the dimension table and Video Performance as the fact table
Created a relationship on VideoID
Measure Creation (DAX)
Total Views, Likes, Comments, Subscribers Gained
Engagement Rate = (Likes + Comments) / Views
📉YoY Views Growth
Average Views by UploadPeriod
Top Category Contribution %
🔹📊 Insights Gained
From the dashboard, I discovered:
Midweek uploads had 18% higher engagement than Weekend uploads.
Tutorials and Product Review videos drove 60% of total views over the last 2 years.
Q4 uploads achieved 15% higher subscriber growth compared to Q1.
Increasing upload frequency from 6 to 10 videos per month boosted average views by 25%.
📉 YoY views grew +22% in 2024 compared to 2023.
Like-to-Dislike ratio improved from 8:1 in 2021 to 12:1 in 2024.

Screenshot
https://github.com/BilalTheAnalyst/Youtube-Analysis-Dashboard/blob/main/YoutubeReport.png

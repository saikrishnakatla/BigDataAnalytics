1. Dataset Description 
1.1 Source: Internal telecom dataset (Telecommunication_Data.csv) containing 5,697 
records. 
1.2 Columns: 
inout_travelling: User status (Travelling/Stationary) 
operator: Telecom operator (e.g., Airtel) 
network_type: Type of network (4G, 5G) 
rating: User rating of network performance (1–5) 
calldrop_category: Call quality category (Satisfactory, Poor Voice Quality, etc.) 
latitude, longitude: Location coordinates (-1 indicates missing data) 
state_name: User state (some missing values) 
month, year: Timestamp of record 
1.3 Data Quality: 
Missing values in state_name and location fields 
Other columns clean and consistent 
Dataset well-suited for telecom network analysis 
2. Operations Performed 
2.1 Data Cleaning & Exploration 
Replaced/handled missing state_name and coordinate values 
Checked unique values in categorical columns (operator, network_type, calldrop_category) 
Summarized numerical columns: calculated min, max, and average for rating 
2.2 Descriptive Analytics 
Operator-wise average, minimum, and maximum ratings 
Distribution of call drop categories 
Rating distribution across network types (4G, 5G) 
2.3 Relationship Analysis 
Comparison of operator vs. rating 
Travelling vs. stationary users’ rating trends 
Network type performance analysis 
Call drop analysis by state and time 
3. Key Insights 
3.1 User Ratings 
Ratings range: 1–5, with an average of ~3.09 
Majority of users report satisfactory experience (ratings 4–5) 
Low ratings (1–2) mostly associated with poor voice quality and travelling users 
3.2 Operator Insights 
Airtel is the most common operator in the dataset 
Airtel average rating: 3.09, min rating: 1, max rating: 5 
Few low ratings indicate minor network issues in specific areas 
3.3 Network Type Insights 
4G is the dominant network type 
5G ratings (if available) are generally higher, showing improved performance 
3.4 Call Quality Analysis 
Satisfactory category dominates 
Poor Voice Quality mostly occurs during travelling or in certain months/regions 
Calls during travel more likely to experience drops 
3.5 Geographic Distribution 
Highest concentration in populated states 
Ratings vary slightly by state → possible coverage gaps 
Some states have incomplete location data 
3.6 Temporal Trends 
Ratings remain fairly consistent from 2021–202 
Minor fluctuations noted in certain months 
4. Recommendations 
4.1 Network Improvement 
Focus on improving voice quality in areas with low ratings 
Enhance coverage for travelling users 
Regularly monitor and maintain high-performance zones 
4.2 Operator & Network Strategy 
Compare operators and incentivize improvements for low-performing regions 
Promote 5G expansion for better user experience 
4.3 Data Collection & Monitoring 
Collect complete location data for better geographic insights 
Track monthly and yearly trends to identify problem areas 
4.4 Customer Experience 
Address complaints from users travelling in low-coverage areas 
Improve network reliability to reduce call drops 
4.5 Future Analytics Opportunities 
Predictive analysis for call drops based on location, network type, and travel status 
Clustering users by rating, location, and operator for targeted improvements 
Trend analysis for long-term network investment planning 
Conclusion: 
The telecom dataset reflects a mid-sized, geographically distributed network 
with generally good user ratings. While most users report satisfactory 
experiences, travelling users and certain regions show lower ratings, 
highlighting areas for network improvement. Operator-specific insights and 
temporal trends provide opportunities for targeted network enhancement, 
predictive modeling, and improved customer experience. 

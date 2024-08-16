
# Active Users and Activity Analysis

This project is a Google Sheets-based analysis of active users and their activities. The task involved statistical analysis of user demographics and the calculation of key user engagement metrics such as Daily Active Users (DAU), Weekly Active Users (WAU), and stickiness.

## Project Structure

The project is structured in four main sheets:

1. **active users**: Contains data about users, including their age, language, game preference, and device information.
2. **activity**: Logs user activity data with details on the game played, activity date, and the total duration of the activity.
3. **DAU**: Provides a summary of the daily active users by calculating the unique users active each day.
4. **WAU**: Summarizes the weekly active users and calculates additional metrics like average DAU per week and the DAU/WAU ratio.

## Analysis

### Part 1: User Demographics Analysis

In the **active users** sheet, the following statistics were calculated based on the users' ages:

1. **Average Age**: The mean age of the users.
2. **Standard Deviation**: The measure of the variation in user ages.
3. **Median Age**: The middle value in the list of user ages.
4. **Interquartile Range (IQR)**: The range between the first and third quartile, giving insight into the middle spread of the ages.
5. **10th Percentile Age**: The age below which 10% of the users fall.
6. **90th Percentile Age**: The age below which 90% of the users fall.

### Part 2: User Engagement Metrics

In this part, we calculated key user engagement metrics using the **activity**, **DAU**, and **WAU** sheets:

1. **DAU Calculation**: For each date in the **activity** sheet, unique active users were calculated and stored in the **DAU** sheet.
2. **WAU Calculation**: Using the **DAU** sheet, the unique active users were aggregated by week in the **WAU** sheet.
3. **Average DAU**: For each week, the average DAU was calculated.
4. **DAU/WAU Ratio**: This ratio was computed to measure user stickiness.

## How to Use

1. Clone this repository to your local machine or open the Google Sheets file linked in this repository.
2. Navigate through the sheets to view the calculations and metrics.
3. Use the provided formulas and structure as a template for your own analyses.

## Conclusion

This analysis provides insights into user demographics and engagement metrics, which are crucial for understanding user behavior and improving product strategies.

# HabitifyVisualizer
A tool to visualize Habitify habits completed over the past days, weeks or months including progress completion color coded pie charts.


# Design & Implementation
- Given the habit completion info from the past week or month, show a color coded chart of what habits you are consistently forming.
    - Red → 0-2 days a week i.e. <30%
    Yellow → 3-5 days a week i.e. 30-80%
    Green → 6-7 days a week i.e. >80%
    
# How To Use:
Simply get the authorization token from Habitify app under Settings > API Credential and paste it into the notebook's AUTHORIZATION_TOKEN cell.
To adjust the range of time for habits analysis, edit TIMEDELTA variable with the number of days, which is set to 30 by default.

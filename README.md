# IT Developments - Project 4

### Welcome to my IT Developments project 4! This repository contains a brief overview of the project.

---

# Project Description and Goal
This project describes the purpose and usage of the UiPath Robotic Process Automation (RPA) bot designed to automate User Acceptance Testing (UAT) for the NWU Tech Trends Telemetry Portal. This RPA bot automates repetitive tasks involved in manually testing the creation of new records on the NWU Tech Trends Telemetry Portal.

---

# How to use this Bot?
### 1. Prerequisites:
- A UiPath Automation Cloud account (or equivalent RPA platform).
- UiPath Studio installed and configured.
- Access to the NWU Tech Trends Telemetry Portal (https://nwutechtrendstelemetryportal.azurewebsites.net).
- The Excel test data file containing records to be used for testing.

### 2. Running the Bot: 
- Open the UiPath Studio project named "NWU Tech Trends Telemetry Portal - User Acceptance Testing".
- Click the "Run" button in UiPath Studio to execute the RPA bot.

---

# What the Bot does
The bot will perform the following actions for each record in the test data file:
1. Read data from the Excel file.
2. Navigate to the web page for creating new records on the NWU Tech Trends Telemetry Portal.
3. Enter the data from each record into the corresponding fields on the web application.
4. Click the "submit" button to create the new record.
5. Navigate to the page displaying the newly created record.
6. Update the data table in UiPath to indicate whether the record creation was successful (passed test) or not (failed test).
7. Update the "Test Passed" column in the original Excel spreadsheet with TRUE or FALSE based on the test outcome.

---
# Reference List
- IT Developments 2023. ***3 October Project 4 Explained***. YouTube. Available at: [https://www.youtube.com/watch?v=5s1-p1okZoc]
- UiPath RPA Learners 2022. ***UiPath : How to read excel data and store into Data table***. Available at: [https://www.youtube.com/watch?v=5r1cBumKSi4]
- SolveUnsolved 2023. ***RPA UAT testing & UAT test document | User Acceptance Testing | RPA Tutorial | UAT | TechieOnWheels***. Available at: [https://www.youtube.com/watch?v=WjKeKFcUcvs]


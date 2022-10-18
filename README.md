# Random-User-API-Performance-Test-Jmeter

## Technology and Tools used in this Project
- JMeter

## Project Scenarios
 - Here Load testing is performed using [Random Data API](https://random-data-api.com/api/v2/users) where the expected load is 120000 for 12 hours. 
   Severall tests has been performed for 60s,300s,600s and 900s load using Jmeter. The tests having TPS breakdown are summarized in excel spreadsheet and the images 
   of tests screenshots are attached in doc file containing HTML report for the last test of 900s having 2500 users.
   
 - And also here stress testing is performed using [Random Data API](https://random-data-api.com/api/v2/users) for finding the bottleneck/stress test point 
   (At which point the system starts to show 1% error) where the expected load is 120000 for 12 hours.Severall tests has been performed for 60s,300s,600s and 900s load    using Jmeter. And The users has have been 166, 833, 1666, 2500, 3500, 4000, 3900 users.  The tests having TPS breakdown are summarized in excel spreadsheet and the    images of tests screenshots are attached for the last test of 900s having 3900 users.

## How to run this project:
 - Clone this project or download the .jmx file in the project directory.

 ## Prerequisite
  - JDK must be installed
  
 ## Jmeter Performance Testing Image
 
 ### Load Test Strategy
 
 ![Load Test Strategy](https://user-images.githubusercontent.com/58990500/193929123-2d73006f-9819-4f90-a2cd-1cccfc035fcb.PNG)

 ### Stress Test Strategy 
 
 ![stress test point](https://user-images.githubusercontent.com/58990500/193929325-dfc0608b-babd-4ff1-b47d-454c02a872d6.PNG)
 
 ### Jmeter Summary (Stress Test Point)
 
![Error 5 47](https://user-images.githubusercontent.com/58990500/193929705-7b3b012b-95c0-49f7-9cf1-af60d0178753.PNG)

### Jemeter Summary (No Error)

![3900](https://user-images.githubusercontent.com/58990500/193929809-fd3deb75-0f84-47fc-ab84-c20d48b4f387.PNG)

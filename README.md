# Final Project Assessment

## **Self-Assessment**: 

#### Our team composition was selected by the instructor, Sohail, for this final project. While he assigned 3 team members to our group, we ended up being only 2 members in the group, having to perform the same work as other teams who were 4 in the group. Because of this, both Michelle and I had to play similar roles throughout the project, having both to manage the GitHub repository, to review each other's work, to work on the ETL, DB and ML phases. We also both contributed to the PowerPoint slides. However, Michelle spent more time on the Machine Learning model, while I focused more energy on the Tableau visualizations.

### My greatest challenge has been to keep version control of our files, and to keep our GitHub repo clean and organized. We both had our own branches, but at times Michelle worked on my branch without letting me know. That let to some files being deleted in my branch. In order to remedy this issue, both Michelle and I spent significant time with our TAs to understand and learn about how to manage our GitHub repo and branches. Eventually, we were able to organize it so that anyone reviewing it would understand our methodology. A second challenge I faced was that Michelle and I were on different time zones, so while she worked during the day, I was 6H ahead of her and therefore had to wait unti late into the night to meet with her. There was really no remedy for that, and I had to drink plenty of coffee to stay awake at night.

## **Team Assessment**:

#### Michelle and I communicated via Slack for quick messages throughout the day, and through Google Meet video calls when we were reviewing our files and preparing for the final presentation. We did not face any challenges with these communication tools. 

#### As a team, our greatest strength was that we were both very responsible contributors to the team, and did not miss any of our internal deadlines. I knew that when Michelle volunteered to do a task on the project, she would get it done as promised. 

## **Summary of Project**:

#### As a **topic**, we have decided to analyze the Air Quality Index (AQI) of 4 different locations (Alaska, California, Washington, DC and Massachusetts) and compare those against the 8 pollutants that are tracked by OpenWeather:

- Carbon monoxide (CO)
- Nitrogen monoxide (NO)
- Nitrogen dioxide (NO2)
- Ozone (O3)
- Sulphur dioxide (SO2)
- Ammonia (NH3)
- and Particle pollution (also known as particulate matter, specifically PM2.5 and PM10)


#### In order to gather our data, we created an Application Programming Interface (API) to capture the historical data since 11/20/20. We ran the data through several **machine learning models** to understand which pollutant had the most impact on the AQIs, for the 4 lcoations, and at each location individually.

##### The first machine learning model we used was the **RandomForestClassifier** to create a supervised learning classifier that uses averaging methods and should reduce varience, as it is combining diverse trees. 

##### The second machine learning model we used was **AdaBoost**, which is a boosting supervised learning classifier aimed to reduce bias and "adapt" around weight values.

#### In summary, our analysis showed that for each of the 4 locations, and for all locations combined, the ozone (O3) levels had the most impact on the overall Air Quality Index (AQI). We were able to visualize these results using both Tableau and PyPlot. Below are some examples of our conclusions:

<img width="752" alt="Screenshot 2021-09-29 081752" src="https://user-images.githubusercontent.com/82544686/135267544-1ae18a4a-9386-49bd-8636-e0563a2b3d12.png">

![Screen Shot 2021-09-29 at 6 56 45 AM](https://user-images.githubusercontent.com/82982952/135255646-8e7134d1-52bb-48f3-95c3-ba7e9202cffe.png)

![Screen Shot 2021-09-29 at 6 57 30 AM](https://user-images.githubusercontent.com/82982952/135255673-8813994a-17c9-4895-87c8-362ec7713a0d.png)

![Screen Shot 2021-09-29 at 6 57 49 AM](https://user-images.githubusercontent.com/82982952/135255720-cf1f4632-cba2-4695-a185-4a87fedaec9b.png)


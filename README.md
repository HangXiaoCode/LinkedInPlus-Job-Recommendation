# LinkedIn_Plus-Job-Recommendation
Interactive website for users to search, save and apply job positions.
Recommend jobs based on users'  job items.

## Main Features
User registration, login and authentication
![as shown](https://github.com/OkayLetsrock/requiredPNGs/blob/main/misc/registration%20UI.png)

User job search based on user's geo_location, favorite jobs and recommend jobs

![as shown](https://github.com/OkayLetsrock/requiredPNGs/blob/main/misc/Job%20Recommendation.png)

## External APIs
GitHub Job API [https://jobs.github.com/api]

Monkey Learn: for keyward extraction [https://monkeylearn.com/keyword-extraction/]

## Flowchart of Back-end Logics
Simplified Back-end Structure
![as shown](https://github.com/OkayLetsrock/requiredPNGs/blob/main/misc/back%20end.png)

## Flowchart of Front-end Logics
Front-end Structure
![as shown](https://github.com/OkayLetsrock/requiredPNGs/blob/main/misc/front%20end%20logics.png)

## Major Impacts
Built web application for users to search, save and apply job positions using **JavaScript, HTML, CSS, and AJAX**.

Implemented **RESTful APIs** on **Java Servlets** to retrieve job descriptions and interreact with database using **MySQL** on **Amazon RDS**, and extracted job keywords with **TF-IDF** algorithm using **Monkey Learn API**.

Recommended jobs using **Content-based Recommendation** algorithm based on user search history and favorites.

Deployed the service to **AWS EC2** with **Docker** container to handle 150+ queries per second.

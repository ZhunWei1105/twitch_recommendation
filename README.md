# twitch_recommendation
There are two files. Jupiter file is for the backend and the other one is for front end.
This is a full-stack web application for users to search twitch resources (stream/video/clip) and users can get recommendations.
For front-end, we utilized React and Ant Design to build a web page with rich + user friendly experience.
We implemented RESTful APIs using Java servlets, retrieved real Twitch resources using Twitch API and stored data in MySQL. 
For the back-end, we designed login/logout features and favorite collection. Also, we explored multiple recommendation algorithms and extracted game information from Twitch resources to implement a Content-based algorithm (avoiding cold start). 
Finally, we used Postman to test GET/POST results and deployed the service to AWS EC2 for better stability.

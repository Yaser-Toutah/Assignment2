# Data Engineering - Assignment2

1. Clone the Repo: `git clone `
2. Go the root level of the app (the cloned app).
3. Execute `docker-compose down`
4. Execute `docker-compose up`
5. Go to Airflow locally (http://localhost:8080/): **Username:** airflow **Password:** airflow

![image](https://user-images.githubusercontent.com/83183385/120042841-87c9e800-c013-11eb-9e83-367ba5301bc3.png)

6. You will see **Assignment_2** Dag is there:

![image](https://user-images.githubusercontent.com/83183385/120042959-c65fa280-c013-11eb-9234-931a9e62762d.png)

7. Open the **Assignment_2** Dag and run it:

![image](https://user-images.githubusercontent.com/83183385/120043103-07f04d80-c014-11eb-898d-7a0b709f5d62.png)

(You can also see in the above image that we have 3 steps/nodes - These are defined ones in dags/assignment2.py file).

8. Access the DB client locally (http://localhost:8000/): **Username:** 1234@admin.com **Password:** 1234

9. You might need to config a DB server (the password in the following image is: **airflow**):

![image](https://user-images.githubusercontent.com/83183385/120043402-8e0c9400-c014-11eb-99ee-dd30cba30852.png)

(The IP Address above is the IP for the **postgres:13** docker image).

10. Finally, you can see the output inside the DB:

![image](https://user-images.githubusercontent.com/83183385/120043521-c7dd9a80-c014-11eb-82d8-58c146f87c5e.png)




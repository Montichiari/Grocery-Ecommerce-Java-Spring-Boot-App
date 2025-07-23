# GetFreshFood Grocery Ecommerce Spring Boot Application
<img width="1916" height="970" alt="image" src="https://github.com/user-attachments/assets/3fb7697d-55d1-4007-99fd-fea7556526c5" />


This project is for NUS GDipSA Batch 60 SA4105 CA, by Team 3 (Dion Yao, Jared Chua, Thina, Hiroyo, Ma Li, Sheng Yi).

## Deployment

To run the app on your machine, you'll need the follow pre-requisites:

- Docker Desktop (or just the Docker daemon) to be installed
- MySQL to be forcefully closed (or anything that occupies port 3306, 5173 and 8080)

Then run the following

```
  docker compose up
```
To login:
Customer Account:
- Email: john.doe@email.com
- Password: Password123!

Staff Account:
- Email: support.staff@email.com
- Password: Admin123!


## Application Stack

Frontend: React, Vite, Typescript, Mantine

Backend: Java Spring

API Documentation: [Click here](https://docs.google.com/document/d/1kjor99ttRCs_Zh_7Qs4eF56zLAih-MexsZRGz5YNFDU/edit?usp=sharing)

## Class/Method Authors

In the Java Spring app, methods are annotated with `@author` to indicate the person who worked on it. For functions/methods that aren't annotated, the group worked on it together.

The React app was worked on by Jared Chua.

## Known Issues

- The `backend` container's logs may indicate that it has failed to connect, but it should automatically restart itself after it has failed a couple of times. This is mainly due to the `db` container not fully ready to accept connections yet.

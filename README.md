# Trip Planner

**Due to the copyright issue, the source code of this application cannot be provided in the public repository**

**Feel free to contact me if you are interested in this project**

## Project Description
Trip Planner is an Android mobile application where users can plan, create and share trips. Users can securely login, customize trips by adding stops such as restaurants, cafes, etc and share their trips with their friends. 

| Authentication                                               | Dashboard                                                    | Plan                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![](https://github.com/RachelYang1999/Image_Storage/blob/main/authentication.png) | ![](https://github.com/RachelYang1999/Image_Storage/blob/main/dashboard.png) | ![](https://github.com/RachelYang1999/Image_Storage/blob/main/plan.png) |

## Project Structure

`backend` folder contains the source code for our **Python Flask** server running remotely on Google App Engine.

`frontend` folder is an **Flutter Android Studio** project for our application.

`Jenkinsfile` contains the pipeline build stages detected by **Jenkins Multi-branch project**.

## Brief System Architecture

![System Architecture](https://github.com/RachelYang1999/Image_Storage/blob/main/Trip_Planner_Archi.png)

### Flutter

Flutter is the frontend framework used in this project which provides us fast development, expressive and smooth UI/UX, and native device support. 

### Flask Web server

Python Flask framework is used for the backend development, which supports us to implement the internal APIs and manipulate with the database.

### Google App Engine

In our development process,  there will be usages of the Standard Runtime Environment which will give the system a fixed amount of resources to host the Flask web server. The Flask web server will be deployed onto Google App Engine where it will run on a container with the standard environment resources. 

### Firebase

Firebase is the primary database service we used for this project. The Firebase Authentication is used to set up the authentication and email verification to the mobile application. Moreover, the Firebase storage is used to store any assets and all collected data.

### External APIs

The Google Maps API is used in order to facilitate a map view on the client-side of the mobile application. The Google Maps API will also be leveraged on the Flask server to enable search by route and search places such as restaurants.

### Jenkins

The server is running on AWS EC2 instance with the name `Saturn`.


### Google PlayStore

The application `Tripit` has already been deployed to Google PlayStore in **Beta Testing (closed testing) stage**.

----

<p align="center">
<b><i>Thank you for reviewing!</i></b>
</p>


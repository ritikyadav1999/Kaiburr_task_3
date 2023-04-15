# Kaiburr Assessment Task-3

#### A simple java springboot application is eployed using Google cloud platform on Google cloud Kubernetes Engine.

## Steps Involved:

#### 1. Creating a cluster on Google Cloud Kubernetes Engine.

![Kubernetes Engine cluster](https://user-images.githubusercontent.com/122474267/232206070-07b81735-b85b-4f11-bb79-ffb2dd8f6e73.png)

#### 2. Fetching the Git Repository

![clonning the repository](https://user-images.githubusercontent.com/122474267/232208321-8d34fad5-fdc9-4bbb-b095-b36f0bb39a08.png)

#### 3. Building the Project Artifacts

![buillding the artifacts 1](https://user-images.githubusercontent.com/122474267/232208220-82afb29c-93ed-4778-b5f5-454dc6904c45.png)
![buillding the artifacts 2](https://user-images.githubusercontent.com/122474267/232208340-597f13a3-1a41-45dc-b8c4-64983909614f.png)
![buillding the artifacts 3](https://user-images.githubusercontent.com/122474267/232208346-d1683c26-f174-485f-a097-041a7a9b2504.png)

Running the application using Jar file 

![running the application using jar file 1](https://user-images.githubusercontent.com/122474267/232208996-d07a37e0-c734-4a52-81ea-96040088a39a.png)
![running the application using jar file 2](https://user-images.githubusercontent.com/122474267/232209010-9133a96c-aa96-41c9-978e-5a83d10f4eab.png)

#### 4. Building the Docker Image for the project and pushing it to Cloud Container Registry

We are using Google Jib plugin for building Docker Image.
Jib builds containers without using a Dockerfile or requiring a Docker installation. We can use Jib in the Jib plugins for Maven or Gradle.

![building the docker image and pushing it to container registry 1](https://user-images.githubusercontent.com/122474267/232208508-f277f35e-4786-4a8d-b496-11ee5db90542.png)
![building the docker image and pushing it to container registry 2](https://user-images.githubusercontent.com/122474267/232208673-1c816b83-4526-42ef-bab4-8fa54662f66f.png)


Google Cloud Container Registry

![container regitry dokcer image 1](https://user-images.githubusercontent.com/122474267/232208851-ac37326e-e4ed-4edb-ba02-e71806d39008.png)
![container regitry dokcer image 2](https://user-images.githubusercontent.com/122474267/232208862-ee58b280-9bc0-464c-a0ea-d9eda2169c7a.png)

#### 5. Checking if the Docker Image is perfectly working or not

![checking docker image 2](https://user-images.githubusercontent.com/122474267/232209036-191d41e2-7e05-4b8b-8975-1c698cb984d2.png)

#### 6. Pushing the Docker Image in the Kubernetes Pods

![Screenshot (131)](https://user-images.githubusercontent.com/122474267/232209198-ee75e79c-0cad-4822-a54e-2bd647a40661.png)
![Screenshot (132)](https://user-images.githubusercontent.com/122474267/232209205-bfa4a8b2-41e4-4141-9d0a-dd6e43226360.png)

#### 7. Exposing to LoadBalancer

![Screenshot (133)](https://user-images.githubusercontent.com/122474267/232209367-5badcace-0661-4bb8-b9f0-d89e87a5007f.png)
![Screenshot (134)](https://user-images.githubusercontent.com/122474267/232209384-f123f380-f51b-4b27-8d66-00f6afa4f175.png)

#### External Ip of pod : 34.28.29.23 
#### port:8080
#### endpoint: /lazy
![Screenshot (135)](https://user-images.githubusercontent.com/122474267/232209397-6bee7b61-2aaf-4502-98c0-b1524b1baa0e.png)
![Screenshot (136)](https://user-images.githubusercontent.com/122474267/232209656-9877c4cf-cfed-4b4c-8b5c-81619d98ab3c.png)






ISOM 4400 FYP
This repository contains a Dockerized application for company resolution programme. 

## Prerequisites 
Docker installed on your system. If you don't have Docker installed, you can download it from [here](https://www.docker.com/products/docker-desktop)
Running the Application To run the application, follow these steps: 

Step 1: 
Pull the Docker Image You can pull the Docker image from the registry using the following command: 
```bash 
docker pull regan20870229/company_resolution_programme
```


Step 2: Run the Docker Container

Once the image is pulled, you can run the application using the following command:

```bash
docker run -p 7860:7860 regan20870229/company_resolution_programme
```

This command maps port 7860 on the host machine to port 7860 inside the container, allowing you to access the application at `http://localhost:7860` in your web browser.

## Accessing the Application

After running the container, you can access the application by navigating to `http://localhost:7860` in your web browser.

Programme Demonstration (Manual Input)

1. Once you have launched the application, here is the homepage.
![[Pasted image 20250502004449.png]]

2. You must provide the company name for both to do the similarity checking

![[Pasted image 20250502004611.png]]
3. After you have provided the company name and other details (if any), you will have to wait for around 60 sec to 75 sec for the serverless side to initialize the backend agents. (Sometimes longer, due to the large demand for the GPUs in worldwide, I highly recommend you to test it during daytime)
![[Pasted image 20250502005316.png]]

Programme Demonstration (CSV Upload)
1. You may upload a .csv file (only csv, others are not accepted)
![[Pasted image 20250502005714.png]]
2. Choose the column name represent the company name and industry and address, you must provide column name for company name
![[Pasted image 20250502010047.png]]
3. After clicking on submit, wait for few seconds to few minutes (depends on your data size), you may download the output or review it in the interface 

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdIih1ibcotPjSxokJ5uui-d29jMiucAhD9SGRLD5EUNsvBBd5M3Mc_oGvwaQX4EEyveae5HnJQOzIuDhkTFOCU322aQ_xgl-jOoM5PIAl3YjNygbpB0tBAcehUKuDKu0ZexTuv4A?key=aZ4ty--BAdjHoZrIX9BVsEdt)

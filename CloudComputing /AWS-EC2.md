## AWS EC2
(AWS Elastic Cloud Compute) 
- It is a cloud service that provides resizable virtual servers, called instances, which you can use to run applications.


## Steps to launch a virtual server:

1. **Go to EC2 service** --> launch Instance 
<img width="1891" height="924" alt="image" src="https://github.com/user-attachments/assets/32135d44-95b1-4290-837a-bd5966e895ba" />

2. **Select the OS**  (Amazon Linux in our case) ---> Instance type(T2 Micro - for free tier)
<img width="1899" height="954" alt="image" src="https://github.com/user-attachments/assets/85ba423d-9c51-48ea-b8af-90d77e736269" />

3. **Key pair** (To connect the server with your laptop)
<img width="911" height="633" alt="image" src="https://github.com/user-attachments/assets/fa4c8a9d-ec35-4d42-a35f-9938d2c20102" />
A file will be downloaded which is supposed to be kept safely.

4. **Network settings** 
   Firewall rules: Allow SSH Traffic from - (Anywhere)
                   Allow HTTP traffic
   <img width="991" height="604" alt="image" src="https://github.com/user-attachments/assets/0108c1c5-0609-4a7e-a336-34477cc283b1" />

5. **No of Instances Needed**
6. **User data if needed to execute something on the server**
     In advanced setting--> User data
   <img width="912" height="610" alt="image" src="https://github.com/user-attachments/assets/89719f52-7552-462e-b424-2cfd4138fe03" />
   Again to host this website publically the IP should be public , so go to network settings--> Auto- assign public IP --> enable
   
7. **Host it publically!!**
   Go to instances--> open the instance id --> copy the public id --> past on another window --> Here you go!!
   <img width="1919" height="900" alt="image" src="https://github.com/user-attachments/assets/4090a2fb-1118-4f12-b4d7-22be76ae3f66" />
   <img width="1919" height="831" alt="image" src="https://github.com/user-attachments/assets/8257327b-58c0-419d-871a-c9598979d39c" />
   <img width="1911" height="953" alt="image" src="https://github.com/user-attachments/assets/9ea6208d-ebf1-40ea-8d7e-acfd1cd468e2" />



   


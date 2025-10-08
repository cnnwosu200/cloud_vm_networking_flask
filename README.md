# cloud_vm_networking_flask

# Flask on Cloud VM (Assignment 2) 

## Student Info
- Name: Chinyere Nwosu
- Cloud Provider: GCP

## Video recording: 
- Zoom/Loom: [(https://drive.google.com/file/d/1pJcCBLI8njZMQzmpGEDiydBT3kTVMBrp/view?usp=sharing)] 

## Steps
### 1. VM Creation
<img width="1920" height="993" alt="vminstance1" src="https://github.com/user-attachments/assets/ff4f0764-b803-4296-a404-208a448e1b60" />


### 2. Networking (Port 5003 Open)
<img width="1920" height="1038" alt="vminstance5003" src="https://github.com/user-attachments/assets/c423dc9f-6d21-48dd-83b3-32d6cae26487" />


### 3. OS Update + Python Install
 ```bash
   sudo apt update && sudo apt upgrade -y
   ```
 ```bash
   sudo apt install git python3 python3-pip python3.13-venv -y
   ```
<img width="1920" height="995" alt="sudoupdates" src="https://github.com/user-attachments/assets/34d3ddbd-987a-4a2d-b643-ab285ec635ad" />

<img width="1920" height="989" alt="sudoinstallpython" src="https://github.com/user-attachments/assets/fad8ab0a-de4c-4c67-a8a7-95e8badd4a7e" />


### 4. Flask App Running
<img width="1920" height="990" alt="Flasklocal" src="https://github.com/user-attachments/assets/5e02f124-30a0-4186-9e7e-32feaf1ed4dc" />

<img width="1920" height="1036" alt="Flaskrunning" src="https://github.com/user-attachments/assets/903607c6-4a1a-41b5-bf33-611a37e3d3f2" />



### 5. Public IP Access
URL: http://34.134.109.17:5003  

<img width="1920" height="1036" alt="Flaskrunning" src="https://github.com/user-attachments/assets/7449ac7f-cd31-4803-bebb-a79f01d2890e" />



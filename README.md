# Ansible Lab Review

## Lab 6
### 6.1, Requirements
Write Roles Ansible:
- Create user.
- Disable SSH Password log in.
- Grant `sudo` permission for user.
- Add Authorized Key for user ssh by `ssh-key`. 
### 6.2, Labbing
* Source: Clone above.
* Result:
![image](https://user-images.githubusercontent.com/88284121/215699659-d41f64bd-c633-4480-a712-27b80dff52ae.png)
* Checking:
##### 1. Creat User
![image](https://user-images.githubusercontent.com/88284121/215700322-e1c679eb-503a-41d7-a0cb-c59d1cdc9bac.png)
![image](https://user-images.githubusercontent.com/88284121/215700385-44c8c8e4-692b-4234-a76e-9c85bb84465f.png)
![image](https://user-images.githubusercontent.com/88284121/215700440-562d6e7e-006e-497b-8fa0-582d47ebdf73.png)
##### 2. Disable SSH
![image](https://user-images.githubusercontent.com/88284121/215700723-baa4a9b3-c0d0-47b7-ae0b-1f1a7159b1ca.png)
![image](https://user-images.githubusercontent.com/88284121/215700786-d2148f47-ace0-4096-a06c-c5cb9d8c9a22.png)
##### 3. Grant `sudo` permission for user
![image](https://user-images.githubusercontent.com/88284121/215701229-84f85919-f44a-4c23-9f3a-c13618ef389d.png)
![image](https://user-images.githubusercontent.com/88284121/215701266-dac33948-5dde-45fd-bf9c-d3ccdc22d48f.png)
![image](https://user-images.githubusercontent.com/88284121/215701331-a069ce51-c1f2-4b98-9126-302177763c9e.png)
##### 4. Add Authorized Key
![image](https://user-images.githubusercontent.com/88284121/215701510-2550d757-de6d-4bf4-bf14-f4c1ed41cebe.png)
![image](https://user-images.githubusercontent.com/88284121/215701558-faf4bf25-4519-4a6e-aa47-4a82b764bd87.png)
![image](https://user-images.githubusercontent.com/88284121/215701629-ae16b035-7a17-43e4-b498-3607e475b9db.png)

## Lab 7
### 7.1, Requirements
Write Roles Ansible:
- Install **DHCP Server** (Both `Ubuntu` & `CentOS`).
- Config **DNS** for domains:
   + test1.com - 1.2.3.4
   + test2.com - 1.2.3.4
### 7.2, Labbing
* Source: Clone above.
* Result:
![image](https://user-images.githubusercontent.com/88284121/216885924-daf188a6-ea88-4749-bf82-b92011d9c3d0.png)
* Checking:
##### 1. Install **DHCP Server** (Both `Ubuntu` & `CentOS`)
![image](https://user-images.githubusercontent.com/88284121/219608722-ee57c075-8cb8-4a98-ae5f-3a5713d0c100.png)
![image](https://user-images.githubusercontent.com/88284121/220574671-dff6bfde-ff2a-401e-b21a-90ddd59ca058.png)
##### 2. Config **DNS** for domains:
* **Ubuntu**:
![image](https://user-images.githubusercontent.com/88284121/216886940-cb837151-48e1-4832-8ede-0512df7808eb.png)
* **CentOS**:
![image](https://user-images.githubusercontent.com/88284121/216887011-9e3aff83-4b2a-4066-92c7-4607ffce9c7d.png)


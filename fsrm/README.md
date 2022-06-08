# FSRM

***

Preparation:

1 Win Server 2016, 1 Windows 10

Network Adapter: VMnet1

Win Server is installed [ADDS](https://github.com/edith2k1/wdsv/tree/main/adds) 

***

1 Install FSRM

![image](https://user-images.githubusercontent.com/100410064/172506977-5b27cf91-332e-41c7-9d6b-c5d4daaccd57.png)

Next 2 times and Install 

2 Create 1 user to test

![image](https://user-images.githubusercontent.com/100410064/172509372-86796b0e-63a1-4bf1-8247-96a435dab209.png)

3 Create Share Folder in Disk C

![image](https://user-images.githubusercontent.com/100410064/172509783-5f833bf3-4aca-45bd-967f-fd7470d0fd29.png)

4 Share this folder to user u1

![image](https://user-images.githubusercontent.com/100410064/172510215-e5a41b2e-1c2d-45bb-87c3-4d70ce10b7ae.png)

5 Go to FSRM

![image](https://user-images.githubusercontent.com/100410064/172510455-5f7b1773-2ef7-44db-86ea-ef9184b95e8d.png)

6 Create Disk Quota

6.1 Create Quota Template

![image](https://user-images.githubusercontent.com/100410064/172510682-c58de2a4-dacb-43eb-a3f6-5a336758b0e9.png)

![image](https://user-images.githubusercontent.com/100410064/172510944-ba045b1b-c762-4d67-b2ff-6d54e2f7eb96.png)

6.2 Create Quota

![image](https://user-images.githubusercontent.com/100410064/172511034-68e1ca47-a70a-47d1-b331-e3ad37d57748.png)

![image](https://user-images.githubusercontent.com/100410064/172511485-30a999ac-7fd2-49cc-8b65-4adca4a81899.png)

This is the result

![image](https://user-images.githubusercontent.com/100410064/172511618-394f0e57-2c2d-41a4-b0e6-0a9385c4d350.png)

6.3 Log in to u1 account to test

![image](https://user-images.githubusercontent.com/100410064/172512224-6da92b51-666e-4c1c-b279-33e4e921cea0.png)

Copy 1 file exceed 1MB to share folder and this is the result

![image](https://user-images.githubusercontent.com/100410064/172512733-b4c1c0f4-32b8-4f33-a63f-fc03986dcf4a.png)

7 Create File Screen

7.1 Create File Group

![image](https://user-images.githubusercontent.com/100410064/172513998-be6b8d8c-8844-4090-84dc-9af317ad016f.png)

![image](https://user-images.githubusercontent.com/100410064/172520637-d852451b-c3cf-425e-a9e3-bd868a4913ef.png)

7.2 Create File Screen Template

![image](https://user-images.githubusercontent.com/100410064/172514530-3be6ef0e-dcaf-462d-881c-56ce8cb8b9e0.png)

![image](https://user-images.githubusercontent.com/100410064/172520684-6bb2e826-3593-4289-ac7d-f417d5e9acc8.png)

7.3 Create File Screen

![image](https://user-images.githubusercontent.com/100410064/172514878-d31c6da6-e3f0-4c5f-a0be-1e01e09f7801.png)

![image](https://user-images.githubusercontent.com/100410064/172520777-0d248ed9-b07d-4b12-a387-5845151c2305.png)

This is the result

![image](https://user-images.githubusercontent.com/100410064/172521210-77c6b00e-bf6a-4138-a3f6-bb72f0ccee00.png)

7.4 Testing

Copy *.txt file

![image](https://user-images.githubusercontent.com/100410064/172520979-8d4dd114-0884-4adf-b53f-e0096fef5abe.png)

Copy *.html file

![image](https://user-images.githubusercontent.com/100410064/172521039-88ba8eb7-c1da-4dbd-81a1-9f64fb4d74b3.png)


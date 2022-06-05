# DHCP

***

Preparation:

1 Win Server 2016, 1 Windows 10

Network Adapter: VMnet1

Win Server is installed [ADDS](https://github.com/edith2k1/wdsv/tree/main/adds)

***

1 Install DHCP

![image](https://user-images.githubusercontent.com/100410064/172046755-4242cf8d-9a73-4e89-92e6-cd79616ae93b.png)

Next 3 times and Install

2 Complete DHCP configuration

![image](https://user-images.githubusercontent.com/100410064/172046906-5627e2bd-bdca-4360-a2e6-dd34b684a8ae.png)

Next -> Commit -> Close

3 Configure DHCP

![image](https://user-images.githubusercontent.com/100410064/172046972-c6ddb5af-bf62-438b-9701-4e858b784df9.png)

3.1 Create a New Scope

![image](https://user-images.githubusercontent.com/100410064/172047087-8ddb1fe4-1353-4ac7-b80e-18fb9cada8dd.png)

Next and Type the Scope Name

![image](https://user-images.githubusercontent.com/100410064/172047107-1aa6070b-18a4-4d06-8a7a-cd4e8026bb4c.png)

Next and provide IP address range that scope distributes

![image](https://user-images.githubusercontent.com/100410064/172047165-a9c5f472-b878-4b08-87f6-c1008b7f679b.png)

Next and provide IP address range that you want to exclude

![image](https://user-images.githubusercontent.com/100410064/172047295-831be136-bfc1-482f-87d0-1701ed70c48d.png)

Next 3 times and provide Default Gateway

![image](https://user-images.githubusercontent.com/100410064/172047367-cad3398a-f40f-4311-a8b4-cdb5cc1d2fe5.png)

Next 4 times and Finish

Refresh IPv4. The result like this

![image](https://user-images.githubusercontent.com/100410064/172047434-2fc2ba30-bca6-4d62-be25-9d8c5b1945aa.png)

4 Testing

4.1 On Win 10 PC, you configure TCP/IPv4 like this

![image](https://user-images.githubusercontent.com/100410064/172047950-f7c1a395-6cab-4eee-b708-66da7f4c13a5.png)

4.2 Open Command Prompt and run these commands

![image](https://user-images.githubusercontent.com/100410064/172048685-98c97ec4-6628-41e4-93ff-906ba0a6ffde.png)

5 Always assign the same IP

5.1 Get Win 10's Physical address (Right-click Ethernet0, choose Status -> Details ...)

![image](https://user-images.githubusercontent.com/100410064/172048312-13dc7111-b37f-40b2-bb05-d8a08eb85402.png)

5.2 Add new Reservation

![image](https://user-images.githubusercontent.com/100410064/172048387-42510b59-f3a3-4e81-aac5-e28a4570f4a5.png)

5.3 Make like this

![image](https://user-images.githubusercontent.com/100410064/172048453-19030045-b1db-442c-8ad3-c2d79dec2697.png)

This is the result

![image](https://user-images.githubusercontent.com/100410064/172048482-16546ef9-485a-49a5-a9f2-39872c70a24a.png)

5.4 Move to Win 10, run these commands

![image](https://user-images.githubusercontent.com/100410064/172048587-a5d0eece-048d-481d-9eb6-6d73903b8225.png)

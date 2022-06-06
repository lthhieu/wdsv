# ADCS and IIS

***

Preparation:

1 Win Server 2016, 1 Windows 10

Network Adapter: VMnet1

Win Server is installed [ADDS](https://github.com/edith2k1/wdsv/tree/main/adds) and [DNS](https://github.com/edith2k1/wdsv/tree/main/dns)

***

1 Install ADCS

![image](https://user-images.githubusercontent.com/100410064/172082478-c15eebdf-4f34-477b-9c9c-837dd0eddcc6.png)

Next 3 times 

![image](https://user-images.githubusercontent.com/100410064/172082775-e1d93fb8-8c0a-451f-bb97-316f5d90a2a3.png)

Next 3 times and Install

2 After installed successfully, you must configure ADCS

![image](https://user-images.githubusercontent.com/100410064/172082964-b74b5830-e124-483d-b2ca-e71b2032bd3f.png)

Next and choose these options

![image](https://user-images.githubusercontent.com/100410064/172083100-58935159-4acb-4286-b00f-12c26067167e.png)

Next 8 times and Configure

![image](https://user-images.githubusercontent.com/100410064/172083408-d8d1d1b2-be54-4d33-bcd2-9ce5a45e19f8.png)

3 Create data and content for 3 sites in Disk C

![image](https://user-images.githubusercontent.com/100410064/172084062-d260e3ee-16f0-4b99-b8ff-1fd501bb6097.png)

![image](https://user-images.githubusercontent.com/100410064/172084314-ddf2dfea-2fbb-4c92-9c38-7dceece18a8a.png)

![image](https://user-images.githubusercontent.com/100410064/172084507-ad96c950-0097-487d-bb50-4aa65a37ae6d.png)

4 Add Websites

![image](https://user-images.githubusercontent.com/100410064/172084681-b635a1b7-25a5-4020-bb4f-0a078e8e8748.png)

4.1 Add web 1

![image](https://user-images.githubusercontent.com/100410064/172084798-bee2a3de-b0bf-4289-9c60-fab7c2feae92.png)

![image](https://user-images.githubusercontent.com/100410064/172084976-b36d20d2-d19d-47fd-8896-ce2d9916586d.png)

Configure Default Document

![image](https://user-images.githubusercontent.com/100410064/172085200-01acc7d1-74bf-4b1f-a5e6-695c0422aa12.png)

Right-click in the background, choose Add ...

![image](https://user-images.githubusercontent.com/100410064/172085261-3f4fd9a9-f029-4f24-b78a-8b5564e36423.png)

Type *web1.html* and OK

![image](https://user-images.githubusercontent.com/100410064/172085374-3ba2dc3d-549b-4670-8998-6a307d066112.png)

Come back Web 1 Home, right-click in the background, choose Bindings ...

![image](https://user-images.githubusercontent.com/100410064/172085578-8bd9f986-1fd2-4f89-a5e6-20f937686098.png)

Choose Add, type is https, choose SSL certificate

![image](https://user-images.githubusercontent.com/100410064/172085796-9d57749f-7109-452f-8999-767251c1ae3b.png)

The result

![image](https://user-images.githubusercontent.com/100410064/172085971-34974b14-c989-4458-b4a2-9ce12a8c2bce.png)

4.2 Add web 2 and web 3

*Do the same 4.1*

You have 3 Websites

![image](https://user-images.githubusercontent.com/100410064/172086481-e140b485-177c-4e9b-8b6e-c04145de62c9.png)

5 Configure DNS

![image](https://user-images.githubusercontent.com/100410064/172086691-7c751655-b3df-41dd-b7ea-54d9135dd1d4.png)

Create 3 Forward Lookup Zones

5.1 web1.vn

![image](https://user-images.githubusercontent.com/100410064/172086823-90459445-7c35-44a2-b638-ec267b7e2887.png)

Next 3 times and type the name

![image](https://user-images.githubusercontent.com/100410064/172086861-adb5b6d3-e2f1-496d-96d8-665284a8a705.png)

Next 2 times and Finish

Add new Host

![image](https://user-images.githubusercontent.com/100410064/172087004-7f1e3351-f1e6-4906-ba9a-c534502cbef9.png)

*192.168.1.2 is the My Server's IP address*

![image](https://user-images.githubusercontent.com/100410064/172087418-37523090-d07a-491a-ba7b-87c230e24332.png)

Add new Alias

![image](https://user-images.githubusercontent.com/100410064/172087629-f25aa0a7-2686-4076-a797-51bae8162163.png)

Browse to the Host name you have created

![image](https://user-images.githubusercontent.com/100410064/172087849-93f3ccbf-20de-4282-99b2-6bd7244fe320.png)

The result like this

![image](https://user-images.githubusercontent.com/100410064/172087970-371ef1bb-ca70-4150-a427-0134dc7edea6.png)

5.2 web2.vn and web3.vn

*Do the same 5.1*

The result like this

![image](https://user-images.githubusercontent.com/100410064/172088310-a798355f-2567-4ef2-8caf-cc67eb6ae55f.png)

6 Refresh the the server

![image](https://user-images.githubusercontent.com/100410064/172089021-b39bdee4-e185-4c7f-a11d-48c60eccc016.png)

7 Testing

Open Win 10, install Chrome app, open Chrome

and type *http://www.web1.vn*, *http://www.web2.vn*, *http://www.web3.vn*, *https://www.web1.vn*, *https://www.web2.vn*, *https://www.web3.vn* to test

![image](https://user-images.githubusercontent.com/100410064/172090816-b8074747-8b5e-4c9b-a3a2-a798d6404a6b.png)

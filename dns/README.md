# DNS

***

Preparation:

1 Win Server 2016, 1 Windows 10

Network Adapter: VMnet1

Win Server is installed [ADDS](https://github.com/edith2k1/wdsv/tree/main/adds)

***

1 Configure DNS

![image](https://user-images.githubusercontent.com/100410064/172044315-3fde4a37-e440-43cf-9b31-d2c099efd0f2.png)

2 When you installed ADDS before, you will have a Forward Lookup Zones *edith.vn*

![image](https://user-images.githubusercontent.com/100410064/172044417-4d44b64c-4b3d-4b67-815f-753872f9a4b5.png)

3 Now, you just create a new Reverse Lookup Zone

![image](https://user-images.githubusercontent.com/100410064/172044491-a7a36a95-8c63-413f-a7d0-28c3dea4c5a3.png)

After Next 4 times

![image](https://user-images.githubusercontent.com/100410064/172044514-46f76793-4b6e-40a7-be1b-45be253eaaa8.png)

Next 2 times, Finish

4 Create a new Pointer

![image](https://user-images.githubusercontent.com/100410064/172044662-e8c4ee83-09a2-4268-a93f-9cfde720fa59.png)

![image](https://user-images.githubusercontent.com/100410064/172044709-08e847fa-c4d7-4285-927c-769880cb13f2.png)

Browse to SERVER -> Forward Lookup Zones -> edith.vn 

![image](https://user-images.githubusercontent.com/100410064/172044789-1463403d-fcaf-475d-803c-e3ead3c5cc80.png)

Click OK

![image](https://user-images.githubusercontent.com/100410064/172044833-3ec4d2da-d3a3-459d-b179-686d25107c44.png)

The result like this

![image](https://user-images.githubusercontent.com/100410064/172044997-19be4612-45fd-4d47-ba50-7b0ea09abb54.png)

5 Test DNS

Move to Win 10 PC, run these commands

![image](https://user-images.githubusercontent.com/100410064/172044978-1421919f-97e3-472a-b409-19d9bbd6f895.png)

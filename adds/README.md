# Active Directory Domain Services

***

Preparation:

1 Win Server 2016, 1 Windows 10

Network Adapter: VMnet1

***

1 Install ADDS

![image](https://user-images.githubusercontent.com/100410064/172041063-96783cce-04f3-492b-960e-26b08a3bfb20.png)

Next 3 times -> Install

2 Promote this server to a domain controller

![image](https://user-images.githubusercontent.com/100410064/172041131-6a05dd83-b624-4c83-9bc3-79bbed3d9334.png)

2.1 Add a new forest

![image](https://user-images.githubusercontent.com/100410064/172041286-051c56d0-e990-4c85-b645-cd829070f811.png)

2.2 Set password

![image](https://user-images.githubusercontent.com/100410064/172041365-afa24aa8-f924-4c60-acef-ff8b18e98e37.png)

Next 5 times -> Install

Wait for a few minutes, the PC will be restart automatically

3 After restarted, set up the IP like this

![image](https://user-images.githubusercontent.com/100410064/172041896-93dc24dc-d9e6-49df-a8a4-5ffa9ef39656.png)

4 Turn off Firewall

![image](https://user-images.githubusercontent.com/100410064/172041984-4b89d707-a335-4045-acc2-449afcdad1de.png)

5 The Result

![image](https://user-images.githubusercontent.com/100410064/172042072-5f9837a7-2f63-4784-ab87-7f0f23c4363d.png)

6 Join Domain

6.1 Set up the IP like this

![image](https://user-images.githubusercontent.com/100410064/172042975-1ca1d88c-01c8-4acc-b89e-2bd895b4fd73.png)

6.2 Turn off Firewall

![image](https://user-images.githubusercontent.com/100410064/172042562-ddd009be-8b14-4fb5-8afc-7029c956953e.png)

6.3 Change domain

![image](https://user-images.githubusercontent.com/100410064/172042654-89e53346-111f-4754-925c-2502ab306dc0.png)

6.4 Provide the domain's password

![image](https://user-images.githubusercontent.com/100410064/172042906-8fc3c0fd-8aa7-4ea8-b6af-8f84a9078f30.png)

6.5 The result

![image](https://user-images.githubusercontent.com/100410064/172042745-e7bc4c4d-4220-4871-9803-523b00ce4036.png)

6.6 After restarted, you jonied Domain successfully

![image](https://user-images.githubusercontent.com/100410064/172042790-6884076d-5869-4254-bfd6-d0fd55dbaa02.png)

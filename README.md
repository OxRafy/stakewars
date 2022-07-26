# Full Setup Stake Wars: Episode III A New Validator

<p align="center">
<img src="https://user-images.githubusercontent.com/73088644/181064280-6cb10912-8eb7-4af4-b054-6bbed66a5f69.jpg"  width="900px"/>
<p>

## Recommended Hardware Requirements

- 4x CPUs; the faster clock speed the better
- 8GB RAM
- 500GB of storage (SSD or NVME)
- Permanent Internet connection (traffic will be minimal during devnet; 10Mbps will be plenty - for production at least 100Mbps is expected)

## Azure Setup

Make sure you have an Azure account or you can register on [Azure](https://portal.azure.com)
If you already have, follow these steps below :

1. Create VM (Virtual Machine)

      <img width="800" alt="azure1" src="https://user-images.githubusercontent.com/73088644/181065021-5d60fbe4-3950-4b15-aa47-2087fc2d1f16.png">
      
      <img width="800" alt="azure2" src="https://user-images.githubusercontent.com/73088644/181065145-942262fe-e667-446c-951d-c734f7d8d9c3.png">   

2. Name the VM, select regional IP and specifications

      <i>*It is highly recommended to choose the type as shown in the picture or at least according to the recommendations</i>

      <img width="800" alt="azure3" src="https://user-images.githubusercontent.com/73088644/181065150-76800796-5b97-495b-93d4-5445a75213fa.png">      
      
   
3.    Choose the authentication type as "password" then set your username and password, it will be used to access CLI
      
      <i>*Save your username and password !</i>
      <img width="800" alt="Untitled" src="https://user-images.githubusercontent.com/73088644/181067805-f55d521c-8670-4f4c-bdd1-3f31d5991e64.png">
 
      
4.    Don't forget to checklist all ports
      <img width="800" alt="Untitled2" src="https://user-images.githubusercontent.com/73088644/181067815-175bc458-9ceb-4d99-925a-6b151324d495.png">
        
      And then click "Review and Create" button on the left bottom
      
5. Waiting for deployment

      <img width="800" alt="azure5" src="https://user-images.githubusercontent.com/73088644/181065160-cfd3fab4-a675-47a8-a657-8e1ddb0f7c93.png">
      
6. Deployment is complete, and go to resource

      <img width="800" alt="azure6" src="https://user-images.githubusercontent.com/73088644/181072761-2cd8401f-0fd6-4f6f-8202-1c3578db3c7b.png">

7. Now you must to upgrade your storage to 500GB

    Stop your VM first

      <img width="800" alt="azure7" src="https://user-images.githubusercontent.com/73088644/181073078-06b53c57-4428-4b82-b3bf-7209110ee908.png">
   

8. Make sure your VM has stopped, you can check it on notification, then go to Disk
   and choose your Disk in the middle

      <img width="800" alt="azure8" src="https://user-images.githubusercontent.com/73088644/181065173-b9d67efa-0466-49fd-bef7-a3544c2f843d.png">
      
9. Go to Size & performance and select 512GB then click "Resize" button

      <img width="800" alt="azure9" src="https://user-images.githubusercontent.com/73088644/181065180-e43fdc3d-761e-437d-b2fb-49772d1416a0.png">

10. Back to your VM Overview and Start your VM

      <img width="800" alt="azure10" src="https://user-images.githubusercontent.com/73088644/181065182-c0c6af9d-aef8-4825-98f4-8c3a9c245649.png">
      
11. Your VM is ready, Congrats !

      <img width="800" alt="Untitled" src="https://user-images.githubusercontent.com/73088644/181075187-0c117b9c-e954-401a-b5aa-860b1dc61fb2.png">
      
      
After that you can access your VPS using `IPv4` that have you created with some app like [MobaXterm](https://mobaxterm.mobatek.net/download.html) or default app like CMD and PowerShell.

## Challenge


You can do this challenge until `August 11th` and fill `Chuck-Only Producer Onboarding Form` [here](https://nearprotocol1001.typeform.com/to/Z39N7cU9). For ID you can fill in your email


| Challenges | Description                            |   Started     |       Ended     | Link                                                              |
| ---------- | -------------------------------------  | ------------- | --------------- | ----------------------------------------------------------------- |
| 001        | Setup NEAR-CLI                         | July 13, 2022 |  August 11, 2022  |[Guide](https://github.com/yantodotid/testnet/blob/main/stakewars/task/001.md) |
| 002        | Setup Wallet dan Run Validator         | July 13, 2022 |  August 11, 2022  |[Guide](https://github.com/yantodotid/testnet/blob/main/stakewars/task/002.md) |
| 003        | Mounting Staking Pool                  | July 13, 2022 | August 11, 2022   |[Guide](https://github.com/yantodotid/testnet/blob/main/stakewars/task/003.md) |
| 004        | Create Monitoring Node Status          | July 13, 2022 |  August 11, 2022  |[Guide](https://github.com/yantodotid/testnet/blob/main/stakewars/task/004.md) |
| 005        | Create Stakewars Guide                 | July 15, 2022 |  August 11, 2022  |-                                                                  |
| 006        | Create Auto Ping with 2 hours interval | July 19, 2022 |  August 11, 2022  |[Guide](https://github.com/yantodotid/testnet/blob/main/stakewars/task/006.md) |
| 007        | Create Data Science for Staking        | July 22, 2022 | September 7, 2022 |-                                                                |


Form for Submission Challenges 5-7 [here](https://docs.google.com/forms/d/e/1FAIpQLScp9JEtpk1Fe2P9XMaS9Gl6kl9gcGVEp3A5vPdEgxkHx3ABjg/viewform).

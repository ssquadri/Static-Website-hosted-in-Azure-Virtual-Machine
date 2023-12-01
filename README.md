# Static-Website-hosted-in-VM

A static website is hosted inside the IIS server in a Windows 2016 Virtual machine in Azure with public IP

Here is a Step-By-Step Process

**Step-1 Create a Virtual Machine(VM) in Azure with Windows server 2016 OS , and make sure ports of RDP,HTTP are enabled**

**Step-2 Once VM is Created establish the Remote Desktop Connection by RDP file and login with credentials**

**Step-3 After you are in the VM , Go to server manager dashboard and add new feature/role**

**Step-4 Now install IIS server**

**Step-5 After Installation of IIS server is complete , Open the IIS Server Management**

**Step-6 Go to the default website and click on Browse to see the website**

**Step-7 Now copy your website HTML code file and paste in the same directory of default website**

**Step-8 Now click browse and you will see your custom website appear** 

**Step-9 close the RDP session and then copy the Public IP of the VM (Make sure HTTP port is enabled)**

**Step-10 Open incognito and paste the Public IP of VM and you will see your website appear**

**Step-11 Delete all the Resources after you are done with your project which includes VM,Vnet,Resource group,NIC Network interface,Public IP,and disk**

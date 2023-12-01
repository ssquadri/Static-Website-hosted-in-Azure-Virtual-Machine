# Static-Website-hosted-in-VM

A static website is hosted inside the IIS server in a Windows 2016 Virtual machine in Azure with public IP

Here is a Step-By-Step Process

**Step-1 Create a Virtual Machine(VM) in Azure with Windows server 2016 OS , and make sure ports of RDP,HTTP are enabled**



![1 Creating A VM.png](https://github.com/ssquadri/Static-Website-hosted-in-Azure-Virtual-Machine/blob/637b9590ae73d2bd6a0bccc54b58204a537d823b/1%20Creating%20A%20VM.png)




![2 VM deployed and running.png](https://github.com/ssquadri/Static-Website-hosted-in-Azure-Virtual-Machine/blob/637b9590ae73d2bd6a0bccc54b58204a537d823b/2%20VM%20deployed%20and%20running.png)




**Step-2 Once VM is Created establish the Remote Desktop Connection by RDP file and login with credentials**



![3 connecting to VM by RDP.png](https://github.com/ssquadri/Static-Website-hosted-in-Azure-Virtual-Machine/blob/637b9590ae73d2bd6a0bccc54b58204a537d823b/3%20connecting%20to%20VM%20by%20RDP.png)




**Step-3 After you are in the VM , Go to server manager dashboard and add new feature/role**



![4 Inside the VM Server manager dashboard.png](https://github.com/ssquadri/Static-Website-hosted-in-Azure-Virtual-Machine/blob/637b9590ae73d2bd6a0bccc54b58204a537d823b/4%20Inside%20the%20VM%20Server%20manager%20dashboard.png)




**Step-4 Now install IIS server**



![5 installing the IIS server inside VM.png](https://github.com/ssquadri/Static-Website-hosted-in-Azure-Virtual-Machine/blob/637b9590ae73d2bd6a0bccc54b58204a537d823b/5%20installing%20the%20IIS%20server%20inside%20VM.png)



![6 installing the IIS server inside VM.png](https://github.com/ssquadri/Static-Website-hosted-in-Azure-Virtual-Machine/blob/637b9590ae73d2bd6a0bccc54b58204a537d823b/6%20installing%20the%20IIS%20server%20inside%20VM.png)



**Step-5 After Installation of IIS server is complete , Open the IIS Server Management**



![7 after installation open the IIS server manager.png](https://github.com/ssquadri/Static-Website-hosted-in-Azure-Virtual-Machine/blob/637b9590ae73d2bd6a0bccc54b58204a537d823b/7%20after%20installation%20open%20the%20IIS%20server%20manager.png)




**Step-6 Go to the default website and click on Browse to see the website**



![8 browse the current default page and see it.png](https://github.com/ssquadri/Static-Website-hosted-in-Azure-Virtual-Machine/blob/637b9590ae73d2bd6a0bccc54b58204a537d823b/8%20browse%20the%20current%20default%20page%20and%20see%20it.png)



![9 default website.png](https://github.com/ssquadri/Static-Website-hosted-in-Azure-Virtual-Machine/blob/637b9590ae73d2bd6a0bccc54b58204a537d823b/9%20default%20website.png)



**Step-7 Now copy your website HTML code file and paste in the same directory of default website**



![Code for webiste.txt](https://github.com/ssquadri/Static-Website-hosted-in-Azure-Virtual-Machine/blob/d8074b33e4f2a76790c709cc29b8faa936eb9398/Code%20for%20webiste.txt)



![Landing page.htm](https://github.com/ssquadri/Static-Website-hosted-in-Azure-Virtual-Machine/blob/d8074b33e4f2a76790c709cc29b8faa936eb9398/Landing%20page.htm)




**Step-8 Now click browse and you will see your custom website appear** 



![10 custom website hosted on IIS server.png](https://github.com/ssquadri/Static-Website-hosted-in-Azure-Virtual-Machine/blob/637b9590ae73d2bd6a0bccc54b58204a537d823b/10%20custom%20website%20hosted%20on%20IIS%20server.png)



**Step-9 close the RDP session and then copy the Public IP of the VM (Make sure HTTP port is enabled)**


![11 copy the Public IP of VM to see the same website.png](https://github.com/ssquadri/Static-Website-hosted-in-Azure-Virtual-Machine/blob/637b9590ae73d2bd6a0bccc54b58204a537d823b/11%20copy%20the%20Public%20IP%20of%20VM%20to%20see%20the%20same%20website.png)




**Step-10 Open incognito and paste the Public IP of VM and you will see your website appear**



![12 paste the Public IP of VM in incognito mode to see the website.png](https://github.com/ssquadri/Static-Website-hosted-in-Azure-Virtual-Machine/blob/637b9590ae73d2bd6a0bccc54b58204a537d823b/12%20paste%20the%20Public%20IP%20of%20VM%20in%20incognito%20mode%20to%20see%20the%20website.png)



![13 website runs in incognito becoz we enabled HTTP port in the VM.png](https://github.com/ssquadri/Static-Website-hosted-in-Azure-Virtual-Machine/blob/637b9590ae73d2bd6a0bccc54b58204a537d823b/13%20website%20runs%20in%20incognito%20becoz%20we%20enabled%20HTTP%20port%20in%20the%20VM.png)



**Step-11 Delete all the Resources after you are done with your project which includes VM,Vnet,Resource group,NIC Network interface,Public IP,and disk**



![14 after completing the task delete the VM along with other resources.png](https://github.com/ssquadri/Static-Website-hosted-in-Azure-Virtual-Machine/blob/637b9590ae73d2bd6a0bccc54b58204a537d823b/14%20after%20completing%20the%20task%20delete%20the%20VM%20along%20with%20other%20resources.png)




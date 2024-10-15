<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1: Setup a Virtual Machine in Azure
- Item 2: Install the osTicket requirements 
- Item 3: Install osTicket itself
- Item 4: Configure permissions and install osTicket

<h2>Installation Steps</h2>
<p>
 Step (1) Creating Virtual Machine in Azure
</p>
<br/>

![VM](https://github.com/user-attachments/assets/0ee67b0b-b96a-475c-879c-ef7567491309)

<p>
Step (2) Enable IIS in Windows and check the box for CGI under World Wide Web Services > Application Development Features.
</p>
<br />

![image](https://github.com/user-attachments/assets/54f8b2fc-c3d6-48b4-87f9-d4d257bdbbfe)

<p>(osTicket requirement step) Click on the MySQL file to download it. After that, I followed the prompts by selecting "Typical". 
</p>
<br/>

![image](https://github.com/user-attachments/assets/f22d4448-b57a-4a8f-b779-bb3f9a7b3852)

<p>
 and then clicking "Next" until the installation was complete.
</p>
<br/>

![SQL](https://github.com/user-attachments/assets/4585eabe-c5b3-419a-8a51-69c392355529)

<p>  
I created a new folder named "PHP" on the C: drive in Windows. Next, I started the installation of the PHP software. I located the software file, right-clicked on it, and selected "Extract All." When prompted to choose a destination, I typed in "C:/PHP," and all the files were extracted to that folder. I accepted all prompts and continued through the installation process until it was finished..
</p>
<br />

![image](https://github.com/user-attachments/assets/f281b579-fb4f-49ee-8fe9-edb9430f1e49)

<p>
To install osTicket v1.15.8, unzip "osTicket-v1.15.8.zip" from the "osTicket-Installation-Files" folder, and copy the "upload" folder to "C:\inetpub\wwwroot." Then, rename the "upload" folder to "osTicket." Finally, reload IIS by opening it, stopping the server, and then starting it again.

![image](https://github.com/user-attachments/assets/b3cd7f09-81b9-4b41-9db5-4924130d5904)
</p>
<br />

![image](https://github.com/user-attachments/assets/b00e18dc-f7cc-47ca-acd3-74fdd9c7b586)

![image](https://github.com/user-attachments/assets/cf8902f1-50ef-48ac-ae52-2517e3e1f279)

![image](https://github.com/user-attachments/assets/408587fb-d8e5-4fb3-902d-5775f673cf5e)



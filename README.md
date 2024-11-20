<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Internet Information Services (IIS)
- MySQL 5.5
- Add All Simple Versions of x86 PHP Up To v7.3
- Install osTicket v1.15.8
- Reload iis (Open IIS, Stop and Start The Server
- Enable Extensions In iis
- osTicket Refresh On Browser
- File Clean Up For Optimal Use

<h2>Installation Steps</h2>

<h2> Adding Internet Information Services

<p>

  ![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/d3a2c914-47a6-4a27-921a-3efa3a16fdcf)
>
</p>
<p>
STEP 1: Install Or Enable Internet Information Services In The Control Panel.
</p>
<br />

<p>
  
![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/0164eebc-24ec-4267-9c0c-735fae557492)
>
</p>
<p>
Go to Programs And Select Uninstall A Program.
</p>
<br />

<p>
  
![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/2d7f0ea3-4453-4dd5-be5d-1692f07d291c)

>
</p>
<p>
When Reaching The "Uninstall or change a program" Screen, Select Turn Windows Features On Or Off On The Left.
  
</p>
<br />


![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/e9b05c55-8668-4017-9fa6-b270aa0a1487)

>
</p>
<p>
Select Internet Information Services In The Dialog Box, Then Click OK.
</p>
<br />


![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/41bb6136-431f-4113-b1a7-71a1257f7bbe)

>
</p>
<p>
Upon installing IIS, search the internet for "Microsoft Web Platform Installer" and download the extension. (Note: Required to install the remaining softwares needed for the osTicket install)
</p>
<br />

<h2> Adding MySQL 5.5

![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/c35998d5-6684-4065-b6ef-dd586baa6626)

>
</p>
<p>

</p>
<br />


<h2> Adding All Simple Versions Of x86 PHP Up To v7.3

![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/521ce0e4-1479-4709-b999-9f511cb75fce)


>
</p>
<p>
Search The Web And Install "Web Platform Installer" And Open "Web Platform Installer". In The Dialogue Box, Search Web Platform Installer To Add "MySQL 5.5" And Search To Add All Simple Versions Of x86 PHP Up Until 7.3.
</p>
<br />

![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/0820e082-987f-4a09-8060-ab5023cb3720)


>
</p>
<p>
Create A Username And Password
</p>
<br />

![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/fd4c7837-c9d8-4949-9998-22efb0de51d1)


>
</p>
<p>
Web Installer Will Attempt To Finish Installing All Of The Prerequisites, But Some Will Fail. Manually Download C++ Redistribuable As Well As PHP Manager. Resume With Installation. Find And Install "PHP Manager" Version 7.38 & Version 1.5.0.
</p>
<br />

![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/f8f28112-e754-41e0-84d3-00441f87c910)


>
</p>
<p>
Install Microsoft Visual C++
</p>
<br />

![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/2f6f8bfb-bbd0-4dd1-99a1-38ecb525234b)


>
</p>
<p>
Install PHP Manager
</p>
<br />

<h2> Installing osTicket v1.15.8

![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/1ac734cd-545c-401f-8edd-7829812373c1)


>
</p>
<p>
Download And Install The osTicket Software. Then, Extract The Zip File once Downloaded.
</p>
<br />

![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/fd12b5f6-e9b7-4b27-beba-a19461f95296)


>
</p>
<p>
Once The osTicket Install Is Completed, Open The Download Folder And Copy Into wwwroot Folder That Was Created From ISS And Reame The Folder "osTicket".
</p>
<br />

![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/9c28a58c-5de0-411c-a43b-3e8cd9e328f2)


>
</p>
<p>
Upload Folder Is Now Named "osTicket".
</p>
<br />

<h2> Reload IIS (Open IIS, Stop And Start The Server)


![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/7a6fa84e-9963-4fb8-bc8e-27534b18fe26)


>
</p>
<p>
Go To TASKBAR, Type IIS In The Searchbar And Open The Program. Restart The Web Server By Selecting The Browse 80 Folder In The Connections Folder. (Sites > osTicket > Browse 80 > Stop > Restart)
</p>
<br />


![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/62ec0dca-cf30-455d-80a2-447b683eea01)



>
</p>
<p>
To Verify The Program Was Properly Installed This Screen Will Be Presented. If You Are Not Able To Access This Page, Go Back And Install The Missing PHP, C++, Or PHP Manager.
</p>
<br />

<h2> Enabling Extensions In ISS


![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/de39ab08-3e49-4399-b39d-c05c7cf18181)


>
</p>
<p>
Enable The Following Extensions: php_imap.dII, php_intl.dII, And php_opcache. Refresh The osTicket Site To Observe The Changes. 
</p>
<br />


![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/f6daf7c5-0413-4375-8b94-2a71350a6493)


>
</p>
<p>
Go To C: > inetpub > wwwroot > osTicket > Include And Right Click The File "ost-sampleconfig.php" To Rename It To "ost-config.php"  .
</p>
<br />


![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/09794418-5614-471f-93bb-6e1cc33d0de9)


>
</p>
<p>
Enable Automatic Persmissions For Everyone In This File By Right Clicking On The File And Selecting Properties > Advanced > Disable Inheritance > Type Everyone In The Next Dialog Box > Select The Full Access Button > Select Apply > Select OK.
</p>
<br />


![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/c351568f-1258-44df-900c-3cb3d1ece968)


>
</p>
<p>
Download And Install HeidiSQL To Have Client Database That Connects To MySQL Which Was Installed Previously.
</p>
<br />


![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/f079a11f-b609-4228-a39d-c7fa9a013375)



>
</p>
<p>
When Creating A Database, You Will Be Required To Use The Username And Password That Was Used To Install MySQL. Create Database By Right Clicking On SSS > New > Database > Name Database osTicket And Click OK.
</p>
<br />



![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/306cb913-82ab-485c-9c20-928d4b707e73)



>
</p>
<p>
Go To The osTicket Intaller In The Browser Tab And Fill Out The Following Information. System Settings > Admin User > Database Settings > Click On "Install Now".
</p>
<br />

<h2> Refresh osTicket Site In The Browser And observe Changed


![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/1c6f2231-c07e-4407-ad24-a9473a357aaa)



>
</p>
<p>
OsTicket Installation Successful.
</p>
<br />


<h2> Cleaning Up Files


![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/95c49e1b-cce6-4b8b-8560-7fd10a9f530e)


>
</p>
<p>
Lastly, Go To C: > inetpub > wwwroot > osTicket And Delete The Setup File. This Will Clean Up Files During Installation To Prevent Future Performance Issues With osTicket
</p>
<br />


![image](https://github.com/JustinPeguero/osticket-prereqs/assets/170198869/945db0eb-ccbe-4db0-8467-616ef71fd853)




>
</p>
<p>
Go To C: > Inetpub > wwwroot > osTicket > Include And Right Click On "ost-config.php" And Select Securities Tab > Advanced > Click Edit (To Change Permissions For Everyone To Only Have Read & Execute By Deselecting The Radio Buttons) > Click On Apply > OK.
</p>
<br />

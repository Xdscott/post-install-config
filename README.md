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

- Create a Virtual Machine in Azure
- Open installation files to install OsTicket and some of the dependencies.


<h2> Post Installation Steps</h2>
<p>
.Configure Roles:
  
    a. Admin Panel -> Agents -> Roles
    
    b.Supreme Admin

</p>

  ![image](https://github.com/Xdscott/osticket-prereqs/assets/125581739/a2dcb0de-e305-4554-a755-426c476df901)

</p>

<p>
.Configure Departments:
  
    a.Admin Panel -> Agents -> Departments
    b.System Administrators

</p>


<p>
  
![image](https://github.com/Xdscott/osticket-prereqs/assets/125581739/dae4aef5-31d9-48ae-8f1b-ddb49f865dd2)

</p>
<p>
.Configure Teams:
  
    .Admin Panel -> Agents -> Teams
  
        .Level I Support
    
        .Level II Support

</p>
<p>

  ![image](https://github.com/Xdscott/osticket-prereqs/assets/125581739/7e20d02c-bda5-4aef-af47-fff004689be7)

</p>
<p>
.Allow anyone to create tickets
  
    a.Admin Panel -> Settings -> User Settings
    
    b.Registration Required: Require registration and login to create tickets  
</p>
<p>
  
![image](https://github.com/Xdscott/osticket-prereqs/assets/125581739/72398dee-74d4-4623-bdf1-6c3b43d1a84d)

</p>
<p>
.Configure Agents (workers)
  
    a.Admin Panel -> Agents -> Add New

        I.  Jane
        ii. John

</p>
<p>
  
  ![image](https://github.com/Xdscott/osticket-prereqs/assets/125581739/57926ce3-4314-440d-ac2d-ba60e16ff030)

</p>
<p>
.Configure Users (customers)
  
    a.Agent Panel -> Users -> Add New
    
        i.  Karen
        ii. Ken

</p>
<p>
  
  ![image](https://github.com/Xdscott/osticket-prereqs/assets/125581739/67134637-7bfe-4de0-baee-6a81f466aca4)

</p>
<p>
  .Configure SLA
  
      a.  Admin Panel -> Manage -> SLA
      
          i.  Sev-A (1 hour, 24/7)
          
          ii.  Sev-B (4 hours, 24/7)
          
          iii.  Sev-C (8 hours, business hours)

</p>
<p>
  
  ![image](https://github.com/Xdscott/osticket-prereqs/assets/125581739/aba8fc58-11f1-4791-a681-b508cb0110f1)

</p>
<p>
  
  .Configure Help Topics

        a.  Admin Panel -> Manage -> Help Topics
  
            i.  Business Critical Outage
      
            ii.  Personal Computer Issues
      
            iii.  Equipment Request

            iv.    Password Reset

</p>
<p>
  
  ![image](https://github.com/Xdscott/osticket-prereqs/assets/125581739/94514eb6-4725-4fc4-98c7-d99511977b6f)

</p>

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
  
![Screenshot 2025-03-09 005518](https://github.com/user-attachments/assets/a14a825a-cb11-40ed-b962-27c3b31c9457)

</p>
<p>
I logged into osTicket using http://localhost/osTicket/scp/login.php. Navigate to Agents in the Admin panel.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 010230](https://github.com/user-attachments/assets/59961bfe-0ed9-4c61-aa48-bd884501d511)

</p>
<p>
Under the Agents tab, click Roles and under Roles, click on View Only.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 010300](https://github.com/user-attachments/assets/c58680af-bb94-474b-ac28-00211f8aed25)

</p>
<p>
Click on Permissions.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 010313](https://github.com/user-attachments/assets/0cec004a-075d-4e3f-af55-72571e18882d)

</p>
<p>
We can see that there are no permissions selected.
</p>
<br /><p>

  
![Screenshot 2025-03-09 010410](https://github.com/user-attachments/assets/dc744bfb-1080-45e0-980e-0a5e18c68869)

<p>
Go back to Roles, click on Expanded Access and go to permissions.
</p>
<br /><p>

  
![Screenshot 2025-03-09 011223](https://github.com/user-attachments/assets/2a0ef26c-d4e8-4562-a85c-3ce1c4df35cc)

</p>
<p>
We can see that most of the permissions are selected.
</p>
<br /><p>

  
![Screenshot 2025-03-09 011421](https://github.com/user-attachments/assets/15e3ed06-c23c-4f14-9e38-640d07e4efc3)

</p>
<p>
Under rolses click on Add New TO create a new role as Supreme Admin.
</p>
<br /><p>

  
![Screenshot 2025-03-09 011735](https://github.com/user-attachments/assets/7006fc85-d4d6-4ef5-a57f-1118debff0e5)

</p>
<p>
  Select all permissions to grant full access to make changes and click on add role.
</p>
<br /><p>

  
![Screenshot 2025-03-09 011751](https://github.com/user-attachments/assets/506baef3-52e2-4faf-b9c5-925a2cd98a6b)

</p>
<p>
  The new role has been successfully added.
</p>
<br /><p>

  
![Screenshot 2025-03-09 011930](https://github.com/user-attachments/assets/da1cdbb7-6070-4abe-b18d-8bf5c08e4fdb)

</p>
<p>
  Under the Agents tab go to departments and delete the Maintenance departmemt so that tickets won't go directly to that department.
</p>
<br /><p>

  
![Screenshot 2025-03-09 012357](https://github.com/user-attachments/assets/72a66964-363f-42ec-990e-55f4bb0229be)

</p>
<p>
Under the Agents tab, navigate to Teams and click on Add New Team.
</p>
<br /><p>
  
![Screenshot 2025-03-09 012453](https://github.com/user-attachments/assets/4475e7fe-c657-4de2-aad5-5a0aa663d4c9)

</p>
<p>
Create an online banking team.
</p>
<br /><p>

  
![Screenshot 2025-03-09 012601](https://github.com/user-attachments/assets/3a057c43-5a73-434a-86fd-07d2ca9a6ba2)

</p>
<p>
The online banking team has been successully added.
</p>
<br /><p>

  
![Screenshot 2025-03-09 012641](https://github.com/user-attachments/assets/36ae8370-1a91-4313-868d-1b2c1c17c932)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><p>

  
![Screenshot 2025-03-09 012917](https://github.com/user-attachments/assets/a3310cf4-2f2f-4e15-8882-177a0695fc1a)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><p>

  
![Screenshot 2025-03-09 013206](https://github.com/user-attachments/assets/6619ec0d-50a4-4535-b14a-4503921fdfbf)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><p>

  
![Screenshot 2025-03-09 013227](https://github.com/user-attachments/assets/6350da30-2a9f-4d56-a515-89a6fa6dd41e)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><p>

  
![Screenshot 2025-03-09 013258](https://github.com/user-attachments/assets/7837a9a5-c20a-480e-810c-58b37bfc0d37)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><p>
  
![Screenshot 2025-03-09 013506](https://github.com/user-attachments/assets/155df3ce-f7c3-40ca-b539-ec2d9ca26617)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><p>
  
![Screenshot 2025-03-09 013801](https://github.com/user-attachments/assets/7b9cfd56-0dde-4bba-9bcf-287d75eeb046)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><p>
  
![Screenshot 2025-03-09 013939](https://github.com/user-attachments/assets/d98124e8-914c-4f4c-99e7-e17c492f5175)

<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><p>
  
![Screenshot 2025-03-09 014209](https://github.com/user-attachments/assets/54dce102-50ae-4db5-8a4e-afc6914165a1)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><p>
  
![Screenshot 2025-03-09 014413](https://github.com/user-attachments/assets/3ea31509-05f2-4a92-9c0d-f81a3b0b6fd6)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><p>
  
![Screenshot 2025-03-09 014432](https://github.com/user-attachments/assets/64ba4ec9-d840-4f1f-b52f-14342a52b0c9)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><p>
  
![Screenshot 2025-03-09 014718](https://github.com/user-attachments/assets/314e8a56-8e2e-402f-ac55-1c81de59e157)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><p>
  
![Screenshot 2025-03-09 014754](https://github.com/user-attachments/assets/020a5c00-9d34-4426-89b4-f91f4b4cd1f2)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><p>
  
![Screenshot 2025-03-09 014835](https://github.com/user-attachments/assets/ba74227b-4e08-490e-8feb-cae347ebbef0)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><p>
  
![Screenshot 2025-03-09 014926](https://github.com/user-attachments/assets/086116aa-6972-4f77-8b31-492023ab5992)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><p>
  
![Screenshot 2025-03-09 014943](https://github.com/user-attachments/assets/a070ebd8-b5b0-4c57-8b3d-c80b910c6fcc)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><p>
  
![Screenshot 2025-03-09 015109](https://github.com/user-attachments/assets/0c7ee232-bc76-45bb-a69e-19e9dafffea7)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><p>
  
![Screenshot 2025-03-09 015212](https://github.com/user-attachments/assets/68f2bfc4-4b24-4d4a-a377-9bd758d7e66a)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><p>
  
![Screenshot 2025-03-09 015258](https://github.com/user-attachments/assets/c8bd33ca-bba0-479d-9549-5863ebc78e53)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><p>
  
![Screenshot 2025-03-09 015351](https://github.com/user-attachments/assets/80fceda6-b777-48b7-a951-6fedbe43c33b)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><p>
  
![Screenshot 2025-03-09 015426](https://github.com/user-attachments/assets/addafe14-3eaa-4b8f-8b2a-aab62ee4469c)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><p>

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Web Server: A compatible web server such as IIS (Internet Information Services) or Apache.
- PHP: Version 7.2 or greater (osTicket recommends PHP 7.4 for optimal performance). Ensure the necessary PHP extensions are enabled (e.g., php_imap, php_mysql, php_mbstring, etc.).
- MySQL Database: A MySQL database server (version 5.5 or later) for storing ticketing data.
- Microsoft Visual C++ Redistributable: Install the appropriate version of Microsoft Visual C++ Redistributable (e.g., 2015-2022) for PHP compatibility.
- osTicket Installation Package: Download the latest osTicket installation files from the official osTicket website or GitHub repository.
  
<img width="1122" alt="Screenshot 2024-11-21 at 7 39 33 PM" src="https://github.com/user-attachments/assets/ef04ca69-2e08-46e6-ae63-af43c15f1dd6">

<p>
Enabling Required Windows Features
In this step, navigate to the Control Panel > Programs > Programs and Features, then select Turn Windows features on or off. Expand the Application Development Features section and enable the necessary features for osTicket installation, such as CGI and other relevant options depending on your setup. Ensure the required boxes are checked, then click OK to apply changes.
</p>
<h2>Installation Steps</h2>

<img width="488" alt="Screenshot 2024-11-21 at 7 40 08 PM" src="https://github.com/user-attachments/assets/4b533145-630f-4fc8-a481-c686859c4b77">

<p>

</p>
<p>
Step 1: Installing Microsoft Visual C++ Redistributable
This step involves installing the Microsoft Visual C++ 2015-2022 Redistributable (x86) package, which is a critical prerequisite for running osTicket. Check the box to agree to the license terms and conditions, then click Install to proceed. Once the installation completes, close the setup window and continue to the next step.
</p>
<br />

<p>
<img width="495" alt="Screenshot 2024-11-21 at 7 47 14 PM" src="https://github.com/user-attachments/assets/894a6c97-69d0-4dea-b8ba-eb8c43e65ce2">

</p>
<p>
Step 2: Installing MySQL Server
Begin the installation of MySQL Server 5.5, a required database for osTicket. This screenshot shows the initial setup wizard. Click Next to continue with the installation process. Follow the prompts in the wizard to complete the setup and ensure MySQL Server is properly configured for osTicket.
</p>
<br />

<p>
<img width="1728" alt="Screenshot 2024-11-21 at 7 48 18 PM" src="https://github.com/user-attachments/assets/fba8b371-044a-49cb-9004-996c95dddb84">

</p>
<p>
Step 3: osTicket Installer and PHP Extensions
This step verifies the prerequisites for installing osTicket. On the left, the osTicket Installer confirms that the required configurations are met:

PHP Version 7.2 or greater (e.g., 7.3.8).
MySQL extension for PHP (module loaded).
Additionally, it lists recommended PHP extensions, such as:

PHP IMAP (for mail fetching).
PHP XML-DOM (for HTML email processing).
PHP Mbstring, Phar, and others for enhanced functionality.
On the right, the IIS Manager shows enabled PHP extensions. Ensure that critical extensions like php_mysql.dll, php_openssl.dll, php_imap.dll, and others are enabled. Adjust PHP settings as needed to meet the requirements before proceeding by clicking Continue in the osTicket Installer.
</p>
<br />

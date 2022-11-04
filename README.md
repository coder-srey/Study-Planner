# Study-Planner
-- Webp project
# Visual Studio Code (VS Code):
Visual Studio Code is a source-code editor by Microsoft, and we used it to edit the various Page and scripts as well as HTML/CSS.<br/>
Download Link: [Download Visual Studio Code - Mac, Linux, Windows](https://code.visualstudio.com/download).
## Steps to install
1. Download the VS Code Installer for Windows.
2. Run the Installer, and you can observe that Installer is Installed in
    C:\Users\ {Username}\AppData\ Local\Programs\Microsoft VS Code
3. VS Code has both User Level and System Level setups available.<br/>
User Level setup is smoother than System Level. As well, System Level Requires Administrator Privileges.
4. Make sure the Windows Build is compatible with the VS Code Installer.

# Git Bash:
Git is an open-source Software Tracker application where you can track projects across different versions.<br/>
Download Link: [Install Git](https://git-scm.com/downloads).

## Steps to install
1. Browse Git Installer from the above link.
2. Click on Download Link for Windows.
3. Go to the Download Location and Extract the file to launch the installer.
4. Allow the app to make changes in the device. Click “Yes” in the dialogue box.
5. Review the GNU Public Licence and Click Next.
6. Choose Installation Location and, after that, the components you want to install.
7. Select the Text Editor you want as Default Editor. (VS Code in this case)
8. You will be asked to rename the Initial Branch. The default is “Master.” 
and you can change the Path Environment.
9. Choose the SSH Client and SSL certifications, Line Endings and Emulators as per your
		preferences. The default options are recommended.
10. Choose the default behaviour of the “git pull” command. 
11. You can install additional customizable and experimental packages
  as per Git Version.
12. Click Finish to complete Installation.

# MySQL Workbench
MySQL Workbench is a unified open-source for creating and managing databases. It provides data modelling and SQL development as well as helps with administration purposes.<br/>
Download Link: [MySQL Downloads](https://www.mysql.com/downloads/)
## Steps to install
1. Go to the link mentioned above and click on MySQL Installer for Windows.
2. Choose the compatible installer and download it.
3. Open the installer file and choose a setup type. Choose Custom.
4. Here, you can install Server, Workbench, and Shell.
5. From the products, choose the desired versions of the above three.
6. Click on Next, and click on execute to install the selected versions.
7. After that, under Type and Networking, choose default choices.
8. For Authentication, use recommended strong password option.
9. In Accounts and Roles, choose the root as username and password.<br/>
(Note: This username and password should be entered in the app.js file to establish
the DB connection or use the username and password of the app.js file, which is	
“newuser” and “Study@123” respectively)						
10. Apply default Windows Settings and execute the installation. 
  Click Finish once completed.

# Node.js and NPM
Node.js is an open-source, cross-platform, back-end JavaScript runtime environment that runs on a JavaScript Engine and executes JavaScript code outside a web browser, which was designed to build scalable network applications.<br/>
NPM (Node Packet Manager) which is a default packet manager for Node.js.<br/>
Download Link: [Node.js](https://nodejs.org/en/download/) and [NPM Packets](http://www.npmjs.com)
## Steps to install
1. Download the Node.js ‘.msi’ installer according to your system.
2. Open the .msi file. Setup Wizard is opened.
3. Welcome Page and following that, the End User Licence Agreement comes.
		  Tick the checkbox and proceed.
4. Select Destination Folder. After that, choose a custom setup if required.
5. Click on Install. Give required Administrator Authorisation Permissions. 
  Click Finish to complete the installation.
6. To make sure the Node.js is installed properly, 
		  Run “C:\Users\Admin > node -v” on Windows Command Prompt.
7. Update the local npm version by running the following Command.
		  “npm install npm -global” to update CLI clients

        
# Establishing the database connection
1. Open MySQL WorkBench.
2. Go to Server.
3. Select “Data Import”
4. Select the “Import from Self-Contained File” option
5. Give the path of the SQL Dump file.
6. Click on the “Import Progress” Button.
7. Click on the “Start Import” Button.
8. In the app.js file, edit the username, password, and database field if required.
   
# Connection with server
1. Open the Git Bash Terminal.
2. Go to folder name “CODE” 
3. Type “npm init” in the terminal.
4. Press enter to keep the default settings.
5. Type “npm install” to install the required package for the system.
6. Type “npm install -g nodemon”.
7. Type “nodemon app.js”, this will start the server, and the application will be online.
8. Go to [http://localhost:3000](http://localhost:3000). (Recommended Browser: Google Chrome)
9. Use Admin’s Login Credentials, i.e. Username: rudra, Password: rudra@123, to start
	experiencing the functionality.



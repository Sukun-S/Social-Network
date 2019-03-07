This repository is the simple reflection of a social networking site like as facebook, twitter, instagram.


 For FrontEnd I have used  Html5, Css3, JavaScript, Jquery, BootStrap4.
 For Backend or for Storing Database I have used Php.
 
 To get started, first we have to create a database, so we need to install a server that can store data.
 The most popular server is called "Xampp", so the process to install Xampp in Ubuntu 18.04lts(as i am using it)is as follows:-
 
 1. STEP 1:-

 Open the Open the link https://www.apachefriends.org/download.html in your favorite browser and download the latest version of LAMPP software that you want for Ubuntu Linux.
 
 2. STEP 2. Open your Terminal and Change directory to the Downloads folder (by default it downloads into the Downloads folder)
 
cd Downloads

STEP 3. Change the execution rights if the installation file, So we can run it as executable file. Execute this command
sudo chmod +x xampp-linux-x64-7.2.3-0-installer.run
1
	
sudo chmod +x xampp-linux-x64-7.2.3-0-installer.run

    Note : The version of XAMPP you’ll download might be different, so change the version in this command accordingly.

For above command to run you have to provide your system’s password

STEP4 .

Run the installer, but don’t close the Terminal.
$ sudo ./xampp-linux-x64-7.2.3-0-installer.run
1
	
$ sudo ./xampp-linux-x64-7.2.3-0-installer.run

A installation set up dialog box will open. In the dialog box, click next(for each step) and move through the process of installation. Once XAMPP is installed, click finish.

xampp install 1

Click Next !

xampp install finish

This will launch the Xampp control panel like shown below. Here Click “Manage servers“.

xampp control panel

Now start all three services by pressing start all button.

start all services

You can also use the commands below to run the Xampp control panel.

    If you use a 64-bit system:
    sudo /opt/lampp/manager-linux-x64.run
    1
    	
    sudo /opt/lampp/manager-linux-x64.run

Once all Apache server is running .  You can use the URL http://localhost/dashboard to open the Dashboard.

apache dashboard

You can also verify if phpmyadmin is running by opening the URL http://localhost/phpmyadmin.



Some More helpful commands

    To set a password, type
    ./lampp security
    1
    	
    ./lampp security

    Press y + Enter. Then enter a new password and re-enter this password again to confirm.
    Start XAMPP
    ./xampp start
    1
    	
    ./xampp start

    Type exit(Enter) to exit the SuperUser
    To start XAMPP, execute this command
    sudo /opt/lampp/lampp start
    1
    	
    sudo /opt/lampp/lampp start
    To stop XAMPP, execute this command
    sudo /opt/lampp/lampp stop
    1
    	
    sudo /opt/lampp/lampp stop

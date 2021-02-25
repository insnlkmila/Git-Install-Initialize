# Git-Install-Initialize

#<ins>Installation Git: How to install Git on Windows</ins>

Before using Git, of course, we need to install Git on the computer you are using. If you're on Windows, here's a Git installation guide:
1. Download the Git installer

Make sure you are downloading the correct Git installation on the official site: [link](https://git-scm.com/downloads). There are two options that support 32bit and 64 bit, according to your computer operating system type. If your operating system supports Windows 64bit, you can download Git which supports 64bit.

2. Start the installation

Click the downloaded Git set up application. The display appears showing the software license. Click next to continue with the installation

<p align="center">
  <img src="https://github.com/insnlkmila/Git-Install-Initialize/blob/main/images/1.jpg" height="300" width="400">
</p>

3. Git Installation Location

Choose a destination for the Git installation location. The installation usually default placed in data **C:\Program Files\Git**. But you can also set the installation destination by clicking the browse button and selecting the folder’s destination.

<p align="center">
  <img src="https://github.com/insnlkmila/Git-Install-Initialize/blob/main/images/2.jpg" height="300" width="400">
</p>


4. Git installation name

After click next in the previous step, a selection of the required components will appear, you can click next to continue the installation after checking the components you need or just click next with the default rules which are usually complete settings for new users. Next, the following folder will appear. It is use to create a Git application naming. You can customize the Git name or keep on Git name for easy search in the Windows Search Menu.

<p align="center">
  <img src="https://github.com/insnlkmila/Git-Install-Initialize/blob/main/images/3.jpg" height="300" width="400">
</p>


5. File Editor

Select the file editor you might use for script Git editing. In this tutorial, I am using **Vim**, you are free to use which file editor. Click next once done.

<p align="center">
  <img src="https://github.com/insnlkmila/Git-Install-Initialize/blob/main/images/4.jpg" height="300" width="400">
</p>


6. Set the Branch name

The name of the branch in the new repostory will become the default masters’ name whenever you use Git if you click **Let Git decide**. Or you can change the master to the name you want with the other one options below.

<p align="center">
  <img src="https://github.com/insnlkmila/Git-Install-Initialize/blob/main/images/5.jpg" height="300" width="400">
</p>


7. Path Environtment

The path environment is used to running every Git command. Choose **Git from the command line and also from third-party software** make it easier for the Windows Command Prompt (CMD) to recognizes Git execution. Click next to continue.

<p align="center">
  <img src="https://github.com/insnlkmila/Git-Install-Initialize/blob/main/images/6.jpg" height="300" width="400">
</p>


8. Terminal Emulator

There are two terminal emulator options you can use is **Command Prompt** or **MinTTY**. Here we are using CMD, and click next to continue with the installation.

<p align="center">
  <img src="https://github.com/insnlkmila/Git-Install-Initialize/blob/main/images/7.jpg" height="300" width="400">
</p>


9. Start the installation process

After a few steps, you will find an install button. Choose additional configurations according to your needs, and click install.

<p align="center">
  <img src="https://github.com/insnlkmila/Git-Install-Initialize/blob/main/images/8.jpg" height="300" width="400">
</p>


Wait for a moments until the installation process is complete. Once the installation already completed, Your git app is ready to use!

##Git Initialization Tutorial

Initialization is carried out to ensure the latest version of the program code you enter is stored correctly. As we discussed before, Git serve as a version control for developers. Initialization also used to save a version of the program code to a new repository for you who are new to Git, so for the next changes you only need to create the initialization name according to your changes. Still confused? Let's get the steps for initializing Git:

1. Select the folder you want to initialize. Type **cmd** in your folder path, the cmd terminal will be displayed quickly in the specific folder you just opened. Don’t forget to click enter once you are done typing cmd in the folder path.
<p align="center">
  <img src="https://github.com/insnlkmila/Git-Install-Initialize/blob/main/images/1.1.jpg" height="200" width="800">
</p>


2. You can type **git init** as shown below. This stage is used to create a new repository. The message you got is initialized empty Git repository in D:/Sistem Arsip which means the new repository was created successfully. However, this repository is still empty.
<p align="center">
  <img src="https://github.com/insnlkmila/Git-Install-Initialize/blob/main/images/1.2.jpg" height="200" width="800">
</p>

3. Then type **git add .** to add new files to the repository. Files in the Sistem Arsip folder will automatically fill the repository. The example folder I use is a simple PHP programming system.
<p align="center">
  <img src="https://github.com/insnlkmila/Git-Install-Initialize/blob/main/images/1.3.jpg" height="200" width="800">
</p>


4. Type **git commit –m "initial commit"** to do Initialization of the first version. The successful initialization is shown below. If there is a change in the source code on your files, you can repeat points 2 and 3. You can replace the naming "initial commit" with the line according to the changes. For example "add system calculator", "change the login system" and other additions or changes.
<p align="center">
  <img src="https://github.com/insnlkmila/Git-Install-Initialize/blob/main/images/1.4.png" height="200" width="800">
</p>


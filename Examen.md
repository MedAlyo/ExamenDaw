# Exam Daw 1

## Index
1. [Introduction](#Introduction)
2. [key words](#key-words)
3. [SSH + Command line](#SSH--Command-line)
4. [Virtualhost](#Virtualhost)
5. [Setting up the VirtualHost Configuration File](#Setting-up-the-VirtualHost-Configuration-File)
6. [Activating VirtualHost file](#Activating-VirtualHost-file)
7. [Conclusion](#Conclusion)
8. [Bibliography](#Bibliography)

## Introduction

This is an exam of DAW of the 1st trimester, where we are tested for our knowledge about: **Github**, **Markdown**, **Apache**, remote work using **SSH** and linux command lines.

## Key words
1. Github
2. Markdown
3. Apache
4. SSH
5. Virtual Host
6. Linux Commands


## SSH + Command line

- Accessing the remote machine  
![Screenshot from 2024-11-11 15-57-26](https://github.com/user-attachments/assets/c9faa7a9-6fac-40fd-a31f-17eb3c4852f2)
- Going to desktop  
![Screenshot from 2024-11-11 16-09-03](https://github.com/user-attachments/assets/277a93f4-a621-4e0a-9992-1f860a5526b3)
-- Creating a txt file that contains my name and putting the result of the *whoami* command, and the name of the command needed to find out who is connected to the machine using ssh.  
![Screenshot from 2024-11-11 16-10-38](https://github.com/user-attachments/assets/34cbb07b-4c34-4220-91a0-62f23ab18cd5)  
![Screenshot from 2024-11-11 16-09-30](https://github.com/user-attachments/assets/f075a395-e246-44ee-abc8-505daf26c344)


## Virtualhost

### Creating the Website
- Creating a folder for our new website in /var/www/ by running  
![Screenshot from 2024-11-11 16-40-10](https://github.com/user-attachments/assets/a1159427-aac6-429b-ac11-fc3c0f35ece7)
- Let’s go into our newly created directory  
![Screenshot from 2024-11-11 16-41-01](https://github.com/user-attachments/assets/edf03092-dc34-4c43-8ba2-07e0731099c2)
- Lets create an HTML file  
![Screenshot from 2024-11-11 16-41-12](https://github.com/user-attachments/assets/2f0938e6-cc4d-4ccb-a329-40d79121a45c)
- The code used in this HTML  
![Screenshot from 2024-11-11 16-43-33](https://github.com/user-attachments/assets/55a372a4-cbf9-43de-8223-c61010db2bf4)


### Setting up the VirtualHost Configuration File

- We start this step by going into the configuration files directory  
![Screenshot from 2024-11-11 16-41-34](https://github.com/user-attachments/assets/8dc6827a-bb98-4b45-a325-57fc6b42d54e)
- Since Apache came with a default VirtualHost file, let’s use that as a base.  
![Screenshot from 2024-11-11 16-41-50](https://github.com/user-attachments/assets/dac03a3c-3f1f-4dce-ba69-3d0d467fd03b)
- Now we edit the configuration file  
![Screenshot from 2024-11-11 16-41-59](https://github.com/user-attachments/assets/171e031f-935f-48a5-9b9c-b7ee8a659aaf)
- We uncomment the ServerName and change it, and We also want the DocumentRoot directive to point to the directory our site files are hosted on.  
![Screenshot from 2024-11-11 17-09-07](https://github.com/user-attachments/assets/67e983b2-6785-4e59-b97d-5c42c118e938)


### Activating VirtualHost file
- we need to activate the virtual hosts configuration file to enable it  
![Screenshot from 2024-11-11 16-42-12](https://github.com/user-attachments/assets/7f335497-1e82-4689-8e15-b79a29792e6e)
- To load the new site, we restart Apache by typing  
![Screenshot from 2024-11-11 16-42-36](https://github.com/user-attachments/assets/3e58d7d5-df94-4a28-8718-abc43a51ecc7)
- End result  
![Screenshot from 2024-11-11 17-03-06](https://github.com/user-attachments/assets/4f8dcebb-75e7-4d65-9ce6-18a8fedb383c)
- If the url doesn't work then go to /etc/hosts in your files, and add 127.0.1.1 daw.ejercicio3.com after the 127.0.1.1 usuario-desktop in your machine (I have another project there)
![Screenshot from 2024-11-11 16-45-09](https://github.com/user-attachments/assets/f95b24be-c2dd-4a80-8531-23483a950bd0)


## Conclusion
In this exam we covered almost all of what we studied in clase, these include: **Github**, **Markdown**, **Apache**, remote work using **SSH** and linux command lines.
It was a straight forward exam, that tested our knowledge in the thing that we studied.

## Bibliography
- [SSH](https://docs.google.com/document/d/1egNlr8BModlaQJlCoySeRyMvsRXn2w5C3YF0Co0-Gf4/edit?tab=t.0)
- [Virtual Host config](https://github.com/MedAlyo/Apache/blob/main/apache%20config.md)


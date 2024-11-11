## Creating the Website

- Creating a folder for our new website in /var/www/ by running  
![Screenshot from 2024-11-11 16-40-10](https://github.com/user-attachments/assets/a1159427-aac6-429b-ac11-fc3c0f35ece7)
- Let’s go into our newly created directory  
![Screenshot from 2024-11-11 16-41-01](https://github.com/user-attachments/assets/edf03092-dc34-4c43-8ba2-07e0731099c2)
- Lets create an HTML file  
![Screenshot from 2024-11-11 16-41-12](https://github.com/user-attachments/assets/2f0938e6-cc4d-4ccb-a329-40d79121a45c)
- The code used in this HTML  
![Screenshot from 2024-11-11 16-43-33](https://github.com/user-attachments/assets/55a372a4-cbf9-43de-8223-c61010db2bf4)


## Setting up the VirtualHost Configuration File

- We start this step by going into the configuration files directory  
![Screenshot from 2024-11-11 16-41-34](https://github.com/user-attachments/assets/8dc6827a-bb98-4b45-a325-57fc6b42d54e)
- Since Apache came with a default VirtualHost file, let’s use that as a base.  
![Screenshot from 2024-11-11 16-41-50](https://github.com/user-attachments/assets/dac03a3c-3f1f-4dce-ba69-3d0d467fd03b)
- Now we edit the configuration file  
![Screenshot from 2024-11-11 16-41-59](https://github.com/user-attachments/assets/171e031f-935f-48a5-9b9c-b7ee8a659aaf)
- We uncomment the ServerName and change it, and We also want the DocumentRoot directive to point to the directory our site files are hosted on.  
![Screenshot from 2024-11-11 16-44-31](https://github.com/user-attachments/assets/cf82ebbc-adf9-4fd8-86cb-81d4c6355add)






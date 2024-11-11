## Creating the Website

- Creating a folder for our new website in /var/www/ by running
![Screenshot from 2024-11-11 16-40-10](https://github.com/user-attachments/assets/a1159427-aac6-429b-ac11-fc3c0f35ece7)
- Let’s go into our newly created directory  
![Screenshot from 2024-11-11 16-41-01](https://github.com/user-attachments/assets/edf03092-dc34-4c43-8ba2-07e0731099c2)
- Lets create an HTML file
![Screenshot from 2024-11-11 16-41-12](https://github.com/user-attachments/assets/2f0938e6-cc4d-4ccb-a329-40d79121a45c)
- The code used in this HTML
![Screenshot from 2024-11-11 16-41-34](https://github.com/user-attachments/assets/1c03cd19-993f-49d8-a3f9-a45c74fbcc52)

## Setting up the VirtualHost Configuration File

- We start this step by going into the configuration files directory  
![Screenshot from 2024-11-11 16-41-50](https://github.com/user-attachments/assets/3f7e5c4a-a45a-42f4-9d66-8b85cf5a54d0)
- Since Apache came with a default VirtualHost file, let’s use that as a base.
![Screenshot from 2024-11-11 16-41-59](https://github.com/user-attachments/assets/45211ebb-1827-4838-be23-02295c603981)
- Now we edit the configuration file
![Screenshot from 2024-11-11 16-42-12](https://github.com/user-attachments/assets/1cac906f-f5dd-4c4f-ac63-11495fc647f4)
- We uncomment the ServerName and change it, and We also want the DocumentRoot directive to point to the directory our site files are hosted on.
- ![Screenshot from 2024-11-11 16-43-33](https://github.com/user-attachments/assets/d1743706-a92f-41dc-8e45-883bade926f2)






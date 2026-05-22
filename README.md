# MULTI-CLOUD ARCHITECTURE

**COMPANY**: CODTECH IT SOLUTIONS  

**NAME**: B RANJITH KUMAR  

**INTERN ID**: CTIS8378  

**DOMAIN**: CLOUD COMPUTING  

**DURATION**: 8 WEEKS  

**MENTOR**: NEELA SANTOSH  

---

# DESCRIPTION OF TASK

In this task, I implemented a Multi-Cloud Architecture project using Amazon Web Services (AWS) and MongoDB Atlas Cloud Database. The objective of this project was to understand how applications can be deployed across multiple cloud platforms and communicate securely with cloud databases.

First, I launched an EC2 virtual machine instance in AWS. The EC2 instance acts as the application server where the Node.js application runs. I selected a Linux-based instance and connected to it using the AWS browser terminal.

After connecting to the EC2 instance, I created a Node.js project and initialized it using npm. Then I installed the required packages such as Express.js and the MongoDB driver. A server file was created to establish a connection between the AWS-hosted application and MongoDB Atlas.

Next, I configured MongoDB Atlas by creating a cloud database cluster. I also created a database user with proper authentication credentials. To allow secure communication between AWS EC2 and MongoDB Atlas, I configured the IP Access List and added the EC2 public IP address.

After the database setup, I executed the Node.js server on the AWS EC2 instance. The server successfully connected to MongoDB Atlas, confirming proper communication between different cloud environments.

This project demonstrates the concept of Multi-Cloud Computing, where one cloud provider hosts the application infrastructure while another cloud provider manages the database services.

Through this task, I learned how cloud platforms can work together in real-world applications. I also gained practical experience in cloud deployment, database connectivity, security configuration, and server management.

Multi-cloud architecture is widely used in modern applications for better scalability, reliability, flexibility, and cost optimization.

---

# OUTPUT

The output of this project is the successful deployment of a Node.js application on AWS EC2 and secure connectivity with MongoDB Atlas cloud database.

---

## 📌 AWS EC2 Instance Running Successfully

This screenshot shows the AWS EC2 virtual machine instance running successfully in the AWS Management Console.

<img width="1919" height="872" alt="image" src="https://github.com/user-attachments/assets/1564bb9f-7372-44cc-9651-9c02184028e2" />

---

## 📌 Node.js Application Setup and MongoDB Connection

This screenshot shows the Node.js project initialization, package installation, and successful connection to MongoDB Atlas from the AWS EC2 terminal.

<img width="1919" height="773" alt="image" src="https://github.com/user-attachments/assets/cd49a46c-2485-42e3-a785-e0ced49dc64e" />

---

## 📌 MongoDB Atlas IP Access Configuration

This screenshot shows the MongoDB Atlas IP Access List configuration where the AWS EC2 public IP address was added for secure database connectivity.

<img width="1919" height="922" alt="image" src="https://github.com/user-attachments/assets/57bf2e50-84e6-41d5-ae14-0c4e43c1d6b7" />

---

## 📌 MongoDB Atlas Cluster Dashboard

This screenshot displays the MongoDB Atlas cluster dashboard showing the active cloud database deployment and monitoring information.

<img width="1919" height="1016" alt="image" src="https://github.com/user-attachments/assets/898c74cd-9ff4-45c2-9993-c49fc7c67ba3" />


---

## 📌 MongoDB Database User Configuration

This screenshot shows the database user configuration in MongoDB Atlas with authentication and access permissions.

<img width="1919" height="924" alt="image" src="https://github.com/user-attachments/assets/2dd7ed84-d2ac-4585-9804-e7161e4afb56" />


---

# TECHNOLOGIES USED

- Amazon Web Services (AWS EC2)
- MongoDB Atlas
- Node.js
- Express.js
- Linux (Ubuntu)
- Cloud Networking
- Multi-Cloud Infrastructure

---

# CONCLUSION

This project successfully demonstrated the implementation of a Multi-Cloud Architecture using AWS EC2 and MongoDB Atlas. The application server was hosted on AWS while the database services were managed using MongoDB Atlas cloud infrastructure.

The successful communication between AWS and MongoDB Atlas confirms that the multi-cloud environment was configured correctly. This task provided hands-on experience in cloud deployment, server configuration, database connectivity, and secure network access management.

The project highlights the importance of multi-cloud solutions in modern cloud computing environments for achieving better scalability, flexibility, reliability, and service integration.


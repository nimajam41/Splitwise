# DongLand Web Application
This repository contains source codes for *DongLand* which is a Persian implementation of [*Splitwise*](https://www.splitwise.com/), a web application in which users can manage their shared expenses and keeps track of them. 

This project has been developed as CE40418 (System Analysis & Design) course project, Spring 2021. Some features of this implementation are different from Splitwise custom design, since the [Persian Project's Definition](https://github.com/nimajam41/Splitwise/blob/main/RFP1-Splitwise.pdf) was different.

**Minimum Cash Flow Algorithm** is also implemented. 

## Get Started
* Open terminal and write following command:
    ```
    git clone https://github.com/nimajam41/Splitwise.git
    ```
     ```
    cd Splitwise
    ```
* for installing requirements, write following command:
     ```
    pip install -r requirements.txt
    ```
    
* Then insert these following commands to connect database and build models
    ```
    python manage.py makemigrations
    ```
    ```
    python manage.py migrate
    ```

* At the end, for running the project, insert this command
    ```
    python manage.py runserver
    ```


## Features
* Users Can be sign up/ login in to our system
* Users can invite thier contacts in the system by email
* Users can add Expense in the System with multiple contacts
* Users can create groups and can add group expense with the group members
* System's administrator has access to see balance report of all users
* System can show balance report of particular User
* System can show balance report of all and particular group

* Users can see and edit their Profile
* Users can set and edit details of expenses including images, location and date
* Group's owner can remove members of group
* System's administrator can remove Users
* Responsive design has been considered and implemented
* High security and Use best practice to write API

## Frameworks
* Django
* Bootstrap

## Authors
- Nima Jamali
    - GitHub: [@nimajam41](https://github.com/nimajam41)
    - LinkedIn: [Nima Jamali](https://www.linkedin.com/in/nima-jamali-5b1521195/)

- Alireza Daghigh
    - GitHub: [@alirezadaghigh99](https://github.com/alierzadaghigh99)

- Ali Ghorbanpour
    - GitHub: [@aliiiqbp](https://github.com/Aliiiqbp)
    - LinkedIn: [Ali Ghorbanpour](https://www.linkedin.com/in/ali-ghorbanpour-aa7b4a167/)

This project is available thanks to all contributors.

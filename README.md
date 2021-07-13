# Bank Management System

Bank management system writtetn in c

* About The Project
* Compile And Running
* Usage

# About The Project

When I researched about bank management on Github I didn't see a good enough source code written in c and I made this project just to see how well I could do it. The project generally uses 'stdlib.h', 'stdio.h' and 'string.h' libraries in the c language, and the system structure is entirely using file layout. Written to be used with servers. Please indicate in the "issues" section if you encounter any errors or problems.

## Images

The images taken from windows terminal.

## ID Entering Screen

![image](https://user-images.githubusercontent.com/79791451/125198253-bc6dc800-e27e-11eb-80f4-283cca56fbce.png)

## PASS Entering Screen

![image](https://user-images.githubusercontent.com/79791451/125198269-d8716980-e27e-11eb-9a16-04954a25c8ba.png)

## User Menu

![image](https://user-images.githubusercontent.com/79791451/125198279-e921df80-e27e-11eb-812c-56f1ab83cd7d.png)

## Admin Menu

![image](https://user-images.githubusercontent.com/79791451/125198291-f8a12880-e27e-11eb-9351-afc35e9db889.png)
.

# Compile And Running

## Compile: make

Compile for users: make main

Compile for admins: make control_panel

Deleting all compiled files: make clear

# Run:

## Windows
For users: main.exe

For admins: control_panel.exe

## Linux:
For users: ./main

For admins: ./control_panel

# Usage

If you type "create" in id screen then you can create new account. So you will receive your id, so please note it.

User commands: deposit() withdraw() change_pass() delete_account() create_account()

Admin commands: create_account() delete_account() change_password() ban_account().

# Folder Structure

|Folder|Description|
|---|---|
|`1_Requirements`| Documents detailing requirements and research |
|`2_Architecture`|Behavioural and Structural UML Diagrams|
|`3_Implementation`|All code and documentation|
|`4_TestPlanAndOutput`|Documents with test plans and procedures and Output|
|`5_Report`|Documentation for Project Evaluation at LTTS|
|`6_ImagesAndVideos`|Code Execution Images and Videos|







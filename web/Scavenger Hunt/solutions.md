![pico22](https://user-images.githubusercontent.com/86824260/126042364-4ef1b40a-86c9-4097-ae74-4a6ce632334b.png)

Description: There is some interesting information hidden around the site. Can you find it?

Steps to Reproduce with Proof of Concept: 
1)	Open the Site.
 
![pico222](https://user-images.githubusercontent.com/86824260/126042367-b4dbb4ee-4eea-4923-853a-5f042cb485d7.png)
 
2)	Just roam around the site and figure out its structure.
3)	Press right click of mouse and select view page source.
4)	Now you can see its source code of the site which contains some scripts and commands.
5)	Copy the first part of the flag and paste it in the flag submission column.

![pico22222](https://user-images.githubusercontent.com/86824260/126042370-9e6e936b-996f-447e-a4d7-6c449978be38.png)
 
6)	Firstly, open mycss.css which was present on the source code of the site.
7)	At the bottom of the code, you can see one command line and copy the second part of the flag and paste it in the flag submission column.
 
 ![pico222222](https://user-images.githubusercontent.com/86824260/126042383-6dc237d9-68d6-4f66-8bb2-8c2532d5cae5.png)

8)	Secondly, open myjs.js which was also present on the source code of the site.
 
 ![pico2222222](https://user-images.githubusercontent.com/86824260/126042385-db3880ca-7877-48ab-aa3b-7c59c1f1de1d.png)

9)	Its command line give us a hint to use robot.txt in the site. Remove /myjs.js from the website address and add /robots.txt
 
 ![pico22222222](https://user-images.githubusercontent.com/86824260/126042388-9759eb94-7a7a-4b8a-b9bf-c0a4e4d500d6.png)

10)	You will get part 3 of the flag and repeat the step 5. 
 
 ![pico222222222](https://user-images.githubusercontent.com/86824260/126042390-8283e6a2-0333-4d16-be8b-33944bdfa871.png)

11)	Its last command line give us another hint and replace /robots.txt with /.htaccess (which is configuration file of apache which is used to make changes in the configuration on a directory basis).
 
 ![pico22222222222](https://user-images.githubusercontent.com/86824260/126042395-337fbb26-3581-40f5-acde-4975c09049e4.png)

12)	You will get part 4 of the flag and repeat the step 5. 
13)	Its last command line give us another hint and replace /.htaccess with /.DS_Store (which mostly belong to Mac OS and holds the information which controls the way a folder will be opened; i.e., the shape and size of the window, the position of the window on the desktop and whether file, folder or icon view has been selected).
 
 ![pico222222222222](https://user-images.githubusercontent.com/86824260/126042399-14e63d8a-c976-43d5-aa54-4ffc134e7b18.png)

14)	You will get part 5 of the flag and repeat the step 5. 
 
 ![pico2222222222222](https://user-images.githubusercontent.com/86824260/126042412-9fe4ec2b-c6be-461d-8ce8-a6b5ff0ce0be.png)

![pico22222222222222](https://user-images.githubusercontent.com/86824260/126042421-245c4fd3-2d3e-4030-9fda-638d40f5b5c1.png)

Payload: Open View Page Source and modify links with     
            
            /robots.txt, /.htaccess, /.DS_Store

![Screenshot (585)](https://user-images.githubusercontent.com/86824260/126042716-08cbd0e3-cd6d-44b5-9d67-024070cfacbe.png)

Description: The factory is hiding things from all of its users. Can you login as Joe and find what they’ve been looking at? 

Steps to Reproduce with Proof of Concept: 
1)	Open the Site.
2)	When you enter details with username of Joe and random password, access will denied.
 
![Screenshot (588)](https://user-images.githubusercontent.com/86824260/126042717-9a154d7c-653e-4cf0-8476-0433487c0066.png)

![Screenshot (589)](https://user-images.githubusercontent.com/86824260/126042739-1e1594b3-b8e9-467a-b935-d89b380372b6.png)

3)	Again, you enter random details of username and password, it will give you access but not that access you wanted.
 
 ![Screenshot (590)](https://user-images.githubusercontent.com/86824260/126042743-2d030d5f-3b38-45b0-b01d-6069e70ceb01.png)

 ![Screenshot (591)](https://user-images.githubusercontent.com/86824260/126042747-27dcec4e-4855-4949-8759-e0f7296b97c2.png)

4)	Right Click and go to Inspect > Application > Cookies > site you accessed. You will get some serious information to change. 
 
 ![Screenshot (592)](https://user-images.githubusercontent.com/86824260/126042749-1ec280ff-40cb-477d-90b8-ecc3352dfeb7.png)

5)	Change username’s value to Joe and press enter.
6)	Change from False to True in admin’s value column and press enter.
 
![Screenshot (593)](https://user-images.githubusercontent.com/86824260/126042751-50c0b193-121c-4432-b496-3aa2a4bdc8b3.png)

7)	Go back to the site and refresh the site.
 
 ![Screenshot (594)](https://user-images.githubusercontent.com/86824260/126042803-dcc3cc5c-814d-46f2-8327-45e2e0474b40.png)

Payload: Open Inspect > Applications > cookies > the site you accessed.     
                                  
                                  Change username’s value to Joe & change from False to True in admin’s value column.

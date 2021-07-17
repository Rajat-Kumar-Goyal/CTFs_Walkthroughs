![pico1](https://user-images.githubusercontent.com/86824260/126041596-0ba38222-2c72-4489-a17d-fb6ee3ca4972.png)

Description: This website can be rendered only by picobrowser, go and catch the flag!

Steps to Reproduce with Proof of Concept: 
1)	Open the Site.
2)	After accessing the site, it starting to show its you’re not picobrowser. Then open Burp Suite.
	
![pico11](https://user-images.githubusercontent.com/86824260/126041614-bfe59b49-feed-4d8a-b49e-7100735a5b53.png)
 
3)	But remember this, your browser’s proxy settings should be configured so that it can be works properly.
4)	If you don’t know how to change this or don’t need to configure your browser’s proxy settings, then you can use Burp Suite’s own embedded Chromium Browser.
5)	Go to Proxy > Intercept, and Turn On the Intercept.

![pico111](https://user-images.githubusercontent.com/86824260/126041623-5e92a59e-30e9-43c3-b360-15e7ac0c9888.png)
 
6)	Now, go back to the site and click on the flag. After clicking flag button, burp suite window will pop up to forward/drop the request.

 ![pico11111](https://user-images.githubusercontent.com/86824260/126041634-ed1ef9c0-3e08-4e6a-b4a5-8cf38d5f4c62.png)

7)	Select whole line of user-agent and remove this and replace with “picobrowser”.

 ![pico111111](https://user-images.githubusercontent.com/86824260/126041642-fc911126-95ec-4211-b29c-eb61f2f7fab1.png)

8)	Then forward the request and go back to the site to get the flag.

![pico1111111](https://user-images.githubusercontent.com/86824260/126041645-0d3ce39f-0b5e-454f-bdb4-3e8fa0bcbb21.png)

9)      Flag successfully found!:sparkle:

Payload: Change the User-Agent in Burp Suite- Proxy > Intercept  
      From Mozilla/5.0 ………… to picobrowser



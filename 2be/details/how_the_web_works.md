## How The Web Works

### Background:

Review the materials below.

* First let's read [MDN HOW WEB WORKS](https://developer.mozilla.org/en-US/Learn/Common_questions/How_does_the_Internet_work)
* Next let's watch a few quick examples of [how the internet works](https://www.youtube.com/watch?v=7_LPdttKXPc).
* And [how IP addresses work](https://www.youtube.com/watch?v=KFooN7Mu0IM   - how IP addresses work).
* Finally let's tie these things together and watch a video about [DNS - what happens when you type an address into a web browser](https://www.youtube.com/watch?v=72snZctFFtA).
* Lastly, let's read a little about [the anatomy of a URL](https://doepud.co.uk/blog/anatomy-of-a-url)

### Questions:

Now we have a better grasp about the internet, and how some of the things are working. Now, let's answer a few questions to check our understanding. Don't be afraid to do additional research (googleing) for an answer. Fork this gist and answer the following questions:

1. Describe, step by step, what happens when I type `www.example.com` into my browser and try to go to the page?
   - client (my device) connects to the internet, wireless, via ISP.
   - OS asks resolving name server(rns).
   - rns looks for Root Name Server.
   - If not found there then, rns goes to top level domain name server (TLD).
   - If not found there then, rns goes to authoritative name server. 
   - TLD is updated with ANS registry information.
   - ANS then returns the IP address which is communicated to the browser which results in the page being displayed.
   
1.  What does HTTP stand for?
 - Hyper Text Transfer Protocol
 
1. 	What protocol does the World Wide Web use?
 - HTTP

1. 	Each computer on the Internet is assigned an IP address, what does IP stand for?
 - Internet Protocol
 
1. 	What does DNS stand for?
 - D.
  * A. Domain Name System
  * B. Digital Number System
  * C. Domain Number System
  * D. Domain Name Service
  * E. Digital Name Service
  
1. 	How are text domain names matched to their respective numeric IP addresses.
 - see above response.
 
1. 	What is the client?
 - E.
  * A. A purchaser
  * B. Internet shopping customer (Consumer)
  * C. The software which requests information from a server (browser)
  * D. The server to which a particular computer sends data
  * E. The computer which the IP address belongs to
  
1. 	What does URL stand for?
  - Uniform Resource Locator
  
1. 	What are protocols
 - D.
 * A. The standardisation of IP addressess
 * B. The DNS standard method for data transfer
 * C.	The standardised network address system
 * D.	The standardised method for transferring data or documents over a network
 * E.	The standardised method for prioratising data or document storage over a network
 
1. What does DNS stand for?
 - Domain Name Server
 
1. what is the `www` portion of a url?
 - subdomain.

1. What is The markup language used for all web documents?
 - XML
 
1. What is the organization that monitors web technologies?
- W3

1. What is the Protocol for transferring web documents on the Internet?
- HTML

1. What matches the domain names with numeric IP addresses?
- ANS - authoritative name server






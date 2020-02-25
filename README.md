**Spam Mailer:**
			A Web Based Application to send upto 50 mails to multiple users at a same time.
			
			
***Note:***

		———————————————————————————————————————————————————————————————————————
		
	 ***!!!This application is build by me for basic understanding of HTML,CSS,JS!!!***
	 
	 ***!!!This application doesn't have a huge functionality(/userful one) but only for fun!!!***
	 
		———————————————————————————————————————————————————————————————————————
	 
	 
**Technology Used:**

*HTML* 		- To build the web page (front end)
*CSS* 		- Styling the Web Pages	 
*NodeJs*	- Backend
*MySQL*		- Database


**Database Structure:**

	*DATABASE NAME* 		= spam_mailer
	*DATABASE PASSWORD*	= spam_mailer
	
	*Table Name:* user
	
	*Structure:*
	
		firstname		-		varchar(50)
		lastname		-		varchar(50)
		username		-		varchar(50) [PRIMARY KEY]
		email			-		varchar(50)	[PRIMARY KEY]
		password		-		varchar(50)
		
		

**How to Run:**

1) Clone the repository to your computer
2) Make use of a powerful editor (I used Visual Studio Code)
3) Install nodejs in your computer		
4) Open the "Spam_Mailer" folder through visual studio code
5) Open terminal and type
		"npm install"
	wait for the packages from the "package.json to install automatically
6) Enter your own email id and password in *.env* file to access the email sending API
7) Type npm start/npm server start to start the application.
	 
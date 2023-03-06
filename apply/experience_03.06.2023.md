## Full Stack 

1.[RSS-Feeds-Edit-Aggregator](https://github.com/my-ihq-prf/lifehacker.com-RSS-Feeds-Edit-Aggregator)

- TASK:  RSS feed parser + administrator interface

	**Task description**
	**Example of project structure**

	To implement RSS feeds on NodeJS/Laravel Parser (for example [https://lifehacker.com/rss](https://lifehacker.com/rss) you can choose on
	at your discretion) using a cron job (or using a worker would be a plus). There will be new publications
	are stored in the database in the 'posts' table.

	1.

	Create CRUD for posts - REST API (or GraphQL API)

	2.

	Create an admin interface SPA (choose React/Vue/Angular2) to manage list form entries with
	pagination, sorting and searching.

	3.

	The ability to create, edit and delete posts should also be implemented in the admin interface

	4.

	Close access to the admin user interface using basic HTTP authentication (in addition, JWT authentication will be implemented).

	5.

	Create a public GitHub repository (Gitlab, etc.). Publish the code. Submit a link

	6.

	```
		.
		├── .env.example
		├── .gitignore
		├── Makefile # Commands for quick assembly and launch of the project (make up, make down, make build
		etc)
		├── README.md # Description of the project (read it, I should have run your app without problems)
		└── src # here's the code!!!
		└── index.js
	```

	**Contents of docker and src folders are shown for demonstration purposes and may vary. Other files and folders may also be present in the project. DBMS of your choice.

	  RESULT: 
		https://github.com/my-ihq-prf/lifehacker.com-RSS-Feeds-Edit-Aggregator
		https://lhk-rss.ify2.repl.co/
		https://lhc-rss.onrender.com/#/


2.[Showyoursport|Nederland](http://trial-showyoursport.000webhostapp.com/)
   
  - TASK: https://github.com/my-ihq-prf/Laravel-Vue-Js-Tailwind-Css
   
  - RESULT: https://trial-showyoursport.000webhostapp.com
   
3.PaaS(correlate.com,gloomshade.com,soelab.no,devshade.com...)

 - (DigitalOcean,Ubuntu 20.04,Docker,Nginx:1.19,php:7.2,node:12,postgres:9.5,redis:6,rabbitmq:3,Webpack,Stylus,VueJs2)
    
	role: principal developer

	my responsibility:
	
		- maintain relevant sites
		- fixing them if needed
		- change the design or add new features upon request
		- registration and maintenance of current certificates for sites via "acme.sh"	
		
	main task:
	
	    - hardcoding
		  since the owner did not have the source codes, I had to work with the generated code to fix many bugs and improve system.
		  
	As for my PaaS experience, I have experience deploying and managing applications 
	
	on a cloud platform that provides ready-to-use tools and services for developers.
		  
			
	

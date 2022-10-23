# cmput404lab7
# Resources used
https://owasp.org/www-community/attacks/xss/  

https://www.bmc.com/blogs/rest-vs-crud-whats-the-difference/#:~:text=CRUD%20is%20an%20acronym%20for,DELETE  

https://www.guru99.com/flask-vs-django.html#:~:text=Key%20Difference%20between%20Flask%20and,for%20easy%20and%20simple%20projects.  

https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS#:~:text=Cross%2DOrigin%20Resource%20Sharing%20(CORS)%20is%20an%20HTTP%2D,browser%20should%20permit%20loading%20resources.


# Questions
Question 0: What is the URL of your python flask_restfull code on github???
https://github.com/Mimi82n2/cmput404lab7

Question 1: How are Flask and Django different? What does Django provide for you that Flask does not?
Django is a full stack web framework while Flask is a more lightweight WSGI framework. Django also provides support for most popular relational database management systems such as MySQL and Oracle while Flask uses SQLAlchemy for its database. Flask also does not support dynamic HTML pages whereas Django does. 

Question 2: What does REST stand for? When I say something is RESTful, what does that mean?
REST stands for REpresentational State Transfer 
RESTful can be used to describe an application programming interface that follows the set of REST architectural constraints. The constraint specifies how resources should be transported over the HTTP protocol.

Question 3: What does CRUD stand for? For each letter in CRUD, give the associated HTTP method.
Create -> POST
Read -> GET
Update -> PUT
Delete -> DELETE

Question 4: What do HTTP 1XX Status Codes mean? HTTP 2xx? HTTP 3xx? HTTP 4xx? HTTP 5xx?
1xx: Information codes - can be used for negotiating transactions between server and client
2xx: Success codes - Indicates successful transaction between server and client
3xx: Redirection codes - Indicated that more action are needed to complete request.
4xx: Client error codes - Problems with request sent by client
5xx: Server error codes - Problem with server given a supposedly valid request

Question 5: What is an XSS attack? Provide one way a site can be vulneratble to an XSS attack.
XSS attack is a type of injection attack where malicious scripts are injected into trusted websites. It can occur when someone sends malicious code in the form of a browser side script to a different end user. The victim's browser executes the script since it came from a trusted website. The script can access cookes, tokens, or other information saved in the victim's browser.

Question 6: What does CORS stand for? What situation in web application development will you need to implement CORS protection?
CORS stands for Cross Origin Resource Sharing.
A CORS header can indicate origins that are permitted to load a server's resources. 
For example, you would need to use CORS if you make a project in Django and React and deploy them on different servers. The backend would need to allow the frontend to access its resources in using CORS. 
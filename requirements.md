
# Non-Functional Requirements

## Analysis & Comparison of Development Environment

### Requirements Team

Technology | MEAN |	Java/Spring Boot | Python/Flask |	Python/Django |	MERN | Clojure
--- | --- | --- | --- | --- | --- | ---|
Skills | 3.8 | 3.8 | 1.7 | 1.8 | 3.8 | 1.5
Features | 4.4 | 3.8 | 3.7 | 3.3 | 4.8 | 3.0
Constraints | 4.5 | 3.3 | 3.3 | 3.0 | 4.5 | 2.5
Usability | 4.3 | 3.0 | 3.3 | 3.0 | 4.0 | 1.3
Support/Community | 4.5 | 3.0 | 4.0 | 4.0 | 3.3 | 2.5
Security | 4.0 | 3.5 | 3.7 | 3.8 | 4.0 | 2.8
Complexity | 3.6 | 4.0 | 4.3 | 4.8 | 3.4 | 4.0
Average | 4.2 | 3.5 | 3.4 | 3.4 | 4.0 | 2.5

Python Flask/Django and Clojure is less skill than MEAN and MERN. Spring boot is less usability and support than MEAN and MERN. MongodDB is used to our back-end application to store data as JSON. Node.js is to implement our application back-end in JS. Express is back-end web application framework running on top of Node.js. Angular/React actually is the similar front-end web app framework, but react is easier to use due to its powerful library.

### Architecture Team

![group evaluation](https://user-images.githubusercontent.com/4582375/30355067-b72ffe36-97e5-11e7-9786-5ada6d989cf6.png)

### Testing Team

Technology	|	MEAN	|	JAVA Spring	|	Python Flask	|	Python Django	|	MERN	|	Clojure
--- | --- | --- | --- | --- | --- | ---| 
Skills	        |	3	|	3	|	3.1	|	2	|	2	|	2
Features   	|	4	|	4	|	3.8	|	4	|	5	|	4
Constraints	|	2	|	5	|	3.1	|	3	|	4	|	4
Usability   	|	3	|	0	|	2.5	|	2	|	4	|	4
Support/Comm. | 3	|	5	|	4	|	3	|	5	|	4
Security    	|	2	|	3	|	3	|	3	|	5	|	3
Complexity	|	3	|	0	|	3	|	3	|	4	|	2
AVERAGE	        |    2.86	|	2.86	|	3.21	|	2.86	|	4.14	|	3.29

![group evaluation](https://user-images.githubusercontent.com/25971844/30355398-0b12fa38-97e8-11e7-9a0d-1f4fa662f831.png)
![group evaluation](https://user-images.githubusercontent.com/25727577/30450761-c4cd82ea-9946-11e7-81a3-ce73dc19575a.png)


### Frontend Selection

The class voted to make a section between the three frontend tools: (a) Angular, (b) VueJS, and (c) ReactJS.  

Technology | 1st | 2nd | 3rd
--- | --- | --- | --- |
Angular | 9 | 12 | 5 | 
VueJS   | 14 | 8 | 6 |
ReactJS | 5 | 6 | 15 |
mtheeb only vote for VueJs
juancleon vote for VueJs
End at JieliChen268

## Conclusion

After analysis of the various development platforms and tools, we've arrived at the following tools:

- Backend:
- Frontend: 
- Middleware:

## Code Management (SCM)

We've unanimously decided that `Github` is to tool of choice for configuration manage (CM) and also for project management (PM). 


# Functional Requirements

### Login Part

- Username shall be email only.

- Capcha Code shall be applied.

- "Remeber Me" shall remember both username and password for same device of current user.

- Application shall allow user to login with other(Google, Twitter) account.

- Application shall have a footer for privacy, about, contact, home, etc.

### Sign up Part



- Emaill address shall be valid.

- Password shall be at least one upcase letter, one lowcase letter, one number, minimum 8 characters and maximum 20.

- Name shall be letters only.

- Date of birth shall be valid date.

- Gender shall be male or female.

- Application shall send confirmation email to register.

- Security Questions shall have default questions for user.

### Forget Password Part

- Application shall ask email to send reset link.

- Application shall ask name and birthday follow by one security question to display user's email if user forget both.








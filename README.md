# NSBE HACKS

### **Won best Use of IBM Watson or BlockChain API award**

Deployed on: https://upturn.herokuapp.com (May take up to 30 seconds to load)

--------

**Name of our app: Upturn**

Nowadays, a lot of student deal with mental stress and anxiety. It is important to address mental health as an important issue, but most of the times, students have a hard time expressing their concerns. Especially students during their college or university go through a lot of things which they don't feel comfortable sharing. 

To solve this problem, we came up with an idea to **build a web application where students can anonymously chat with a person who can guide them through their hard times**. But before a student is connected to a mentor, IBM's Watson Assistance take cares of the initial chat with the student to figure out what will be the best supporting options for the student.

This application **integrates IBM Watson Assistance** with an online application using **React and Node.js**. We are in development of the product, but it is at its initial stage. Currently, the Watson Assistance is connected to the backend of the application, and the backend is connected to the frontend. The reason behind separating the back and front end is the security reasons. It makes the app more secure beacuse hackers cannot easily get the authorization information from the backend.

----

### Deploying on Heroku:

Login:

```
<go to heroku website and create a new web app w/ same name as {your project name here}>
heroku login
git init
heroku git:remote -a {your project name here}
```

Deploy

```
git add -A
git commit -m "{your message here}"
git push heroku master
```

##### Modifying/commiting :

```
git add -u
git commit -m "{your message here}"
git push heroku master
```

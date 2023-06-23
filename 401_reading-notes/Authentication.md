# Readings: Authentication

**Authentication** 💻📒

  ***why this topic matters as it relates to what you are studying in this module?***
    To ensuring the security and integrity of applications.
__________________________________________

#### Securing Passwords

**1.** **Explain to a non-technical friend how you would safely hash and store a password.**
Passwords are securely stored by  applications using a process called hashing,when the user create a password, this password will converted into a scrambled string of characters called a (hash) using a mathematical function. This hash is unique to your password and this password it is impossible to reversed to know the original password.
When the user enter his password to log in to the application, the application takes this entered password, hashes it again, and compares the resulting hash with the stored hash, then If the hashes match, it means the user entered the correct password, and he can access to his account.
also to make the password more secure there is an addition we can used it for that called (salt),salt is added to user password before it is hashed. The salt and the hash are stored together in the database.
this ways make it extremely difficult for anyone to know the passwords, thats ensuring the security of our accounts and keeping our personal information safe.

**2.** **What is Bcrypt?**
Bcrypt is a cryptographic algorithm that transforms a password into a hash. It utilizes salting and a cost factor to make the passwords strong and to ensure  security. Bcrypt is highly regarded for its strength and efficacy in safeguarding user passwords, making it a widely preferred option for password storage in numerous applications.

**3.** **Why might you use something like Bcrypt?**
To increase the security of stored passwords,thats makes it extremely difficult for anyone to retrieve  the original passwords from the hashes.
__________________________________________

#### Basic Auth

**1.** **What is Basic Authentication?**
Basic Authentication is used method for authenticating users in web applications. It include sending the username and password as normal text via the network, encoded in Base64 format. then the server will check he credentials and grants access if they are valid or not valid.

**2.** **What properties are necessary in the header of a Basic Auth request?**
The Authorization

**3.** **How are username:password in Basic Auth encoded?**
Using the Base64
____________________________________________

#### OWASP auth cheatsheet

**1.** **Define the authentication process to a non-technical recruiter.**
When a user wants to access an account for example, he must provide some form of identification,like a username or email or phone, along with a secret piece of information known as a password,so Authentication used to ensure that only authorized users can access to the application or to an service.

**2.** **How should your error messaging respond (both HTTP and HTML)? Why?**
Error messaging must be in  in HTTP responses and HTML pages also, to provide clear feedback to the users when they faced an error.
because the error messaging is very important to help users to understand what the problem,  this error messaging will guide them on how to resolve it if possible, and when the error messaging be clear it will  enhance the user experience.

**3.** **Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.**
OWASP fundamentals is very important. it is provides a set of guidelines and security controls to ensure protect user accounts and the sensitive information,by following OWASP recommendations, the developers can implement a strong password policies, and  protect against  attacks, and reduce the common risks.
___________________________________________

## Things I want to know more about:

I want to know more information about authentication
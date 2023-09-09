# Reading: API Integration:

#### Review API Server Build:

**1.Explain the different between a query string parameter and a path parameter.**
>
> *Query String Parameter:* **A query string parameter is a way to provide extra data to a web server by attaching it to the end of a URL. It usually consists of a key-value pair in the format of key=value, preceded by a question mark (?) in the URL. Query string parameters are commonly employed for tasks such as data filtering or sorting.**
>
>*Path Parameter:* **In contrast, a path parameter is a segment within the URL path itself, designed to identify a specific resource or endpoint. Path parameters are typically enclosed within curly braces ({}) within the URL path and can contain values that are crucial for accessing the intended resource. They serve the purpose of routing requests to the appropriate endpoint based on the provided values.**


**2.What would our API URL with a path id parameter be given the following information:**
>
>* Domain: http://our-site.com
>
>* v3
>
>* model name: stuff
>
>* id: things
>
>The API URL with a path id parameter would look like this: http://our-site.com/v3/stuff/things 


**3.We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.**
>**Think of an "interface" in a dynamic API like a universal remote control. This special remote can be used to control all sorts of gadgets like TVs, DVD players, and music systems. It has buttons and commands that are made to work with different devices. So, you can use this one remote to easily control all your gadgets without needing separate remotes for each.**
>
>**In the world of software, an "interface" does something similar. It's like a set of rules that allow different computer programs to understand and talk to each other, even if they were made by different people. It's like making sure all your gadgets can understand the commands from that one universal remote, so they can work together smoothly.**

#### Review Auth Server Build:

**1.Describe how you would use middleware to implement basic and bearer auth.**
> **Basic Authentication: Middleware plays a role in applying Basic Authentication by examining incoming requests to a server. It verifies whether the request contains a username and password, typically transmitted as a Base64-encoded string within the request headers. If the provided credentials are valid, the request is permitted to proceed; otherwise, access is denied.**
>
>**Bearer Authentication: When it comes to Bearer Authentication, middleware checks for a token (usually a JSON Web Token or JWT) in the request headers. If a valid token is found, the request is granted access; otherwise, access is restricted.**

**2.Describe the handshake necessary to implement OAuth.**
>**OAuth involves a series of steps where three main parties are involved: the user, the client application, and the OAuth server (typically managed by a third-party service). Here's a simplified explanation of how this process works:**
>
>* **The user starts by logging into a client application.**
>
>* **The client application asks the user for permission to access specific resources on their behalf.**
>
>* **This request for permission is sent by the client application to the OAuth server.**
>
>* **If the user grants permission, the OAuth server provides the client application with an access token.**
>
>* **With this access token, the client application gains the ability to access the user's protected resources on the server.**
>
>* **In essence, OAuth establishes a secure way for applications to access a user's data without requiring the user to share their username and password directly with the application.**

**3.Describe how Role Based Access Control works to a non-technical friend.**
>**Think of RBAC like a university with a doorman. The doorman checks your special badge (your role) and only allows you to enter specific parts of the university. This system is like a security guard for computer systems and data, making sure that only the right people can access certain things and helping to keep everything safe.**
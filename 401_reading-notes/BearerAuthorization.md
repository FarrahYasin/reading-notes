# Reading: Bearer Authorization

**Bearer Authorization** 💻📗

  ***why this topic matters as it relates to what you are studying in this module?***
    To ensuring the security and its important for user Experience
______________

#### Intro to JWT

**1.** **What is a JSON Web Token (JWT)?**
A JSON Web Token (JWT) it is a way to securely transmit information between parties as a JSON object. A JSON Web Token used for authentication and authorization also in web applications. A JSON Web Token consist of these three parts:
**1. Header:** it contains data about the token like the hashing algorithm used to generate the signature.
**2. Payload:**  it contains the actual data being transmitted. It consists of a set of key-value pairs that represent statements about the entity else data. it can contain a standard claims  "exp" for expiration time.
**3. Signature:**is created by combining the encoded header and encoded payload, and a secret key using by using also a specified algorithm. The signature ensures the integrity and  verify that the token is secure.

**2.** **When should we use JSON Web Tokens?**
for applications that need to securely transmit information between parties. They are especially well-suited for applications that need to be able to verify the identity of the sender and the integrity of the information such as:Verify the authenticity of a message
and
Authenticate users in a single sign-on (SSO) system

**3.** **Claims are expected in which structural component of a JWT?**
in the payload ,its a JSON object that contains the claims, which are statements about the subject of the token. The claims can be used to represent any type of information, such as the user's identity, or the expiration time of the token.

______________


#### Are JWTs Secure?

**1.** **If I get a JWT and I can decode the payload, how can we call that secure?**
A JWT is secure because it is signed with a secret key. thats means anyone who want to decode the payload will not able to do that because to do taht he need to know the secret key. If you can decode the payload, it means that you know the secret key sure, which means that you are the intended recipient of the JWT.

**2.** **If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature**
The secret key used to sign and the algorithms used to encode and decode the JWT

**3.** **Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.**
we must use a secure encryption method to encrypt the concatenated content, to ensures that even if the content is intercepted during transit, it remains unreadable and confidential, also choose a strong encryption algorithm and use an encryption tool or software to encrypt the content.

______________

#### JWTs Explained

**1.** **Why use JWT?**
it used as authorization tokens in web applications.it is very small, which makes them ideal for transmitting over HTTP headers and JWTs contain all the information they need to be verified, which means that they don't need to be stored in a database. it also can be signed or encrypted, which makes them more secure.

**2.** **JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.**

JWTs are akin to sending a secret message in a sealed envelope. Just as one would write a message on paper, seal it in an envelope, and give it to a friend with the key to open it, JWTs facilitate secure communication. However, instead of an envelope, JWTs employ a JSON object that is compact and self-contained. This allows for effortless transmission over HTTP headers, making them a practical means of securely conveying information.

**3.** **What are the three components (the structure) of a JWT signature?.**
**1. Header:** it contains data about the token like the hashing algorithm used to generate the signature.
**2. Payload:**  it contains the actual data being transmitted. It consists of a set of key-value pairs that represent statements about the entity else data. it can contain a standard claims  "exp" for expiration time.
**3. Signature:**is created by combining the encoded header and encoded payload, and a secret key using by using also a specified algorithm. The signature ensures the integrity and  verify that the token is secure.


______________

## Things I want to know more about:

I want to learn more information about Bearer Authorization
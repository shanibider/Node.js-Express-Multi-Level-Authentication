# Authentication and Security in JavaScript with Node.js, Express.js, EJS, and PostgreSQL 🔑🔒 <img height="90px" align="right" src="https://github.com/shanibider/Authentication-and-Security-Node-Express-PostgreSQL/assets/72359805/afc67c5a-7474-441f-82a4-d1945ca4dd34">

Concepts and tools to develop robust authentication and security systems features in JavaScript applications, using:
#### JavaScript, Node.js, Express.js, EJS, and PostgreSQL. <img height=20px src="https://skillicons.dev/icons?i=postgresql"> <img height=20px src="https://skillicons.dev/icons?i=express"> <img height=20px src="https://skillicons.dev/icons?i=nodejs"> <img height=20px src="https://skillicons.dev/icons?i=js">


<div align="center">
<img height="300px" src="https://github.com/shanibider/Authentication-and-Security-Node-Express-PostgreSQL/assets/72359805/3f36e0ec-b21d-4b97-a99a-1dec29bf00e4"></div>


## Related Links 🔗
- [x] [AES256 encrypt & decrypt online](https://encode-decode.com/aes256-encrypt-online/)
- [x] [Try the Ciser Chiper](https://cryptii.com/pipes/caesar-cipher)
- [x] [Password Strength Checker](http://password-checker.online-domain-tools.com/)
- [x] [Have I Been Pwned?](https://haveibeenpwned.com/)


## Why Authentication and Security Matter🔒

Authentication ensures that users are who they claim to be, while security measures protect sensitive user data from unauthorized access. Without robust authentication and security mechanisms, applications are vulnerable to attacks such as data breaches, identity theft, and unauthorized access.

## Encryption for Data Security🔓

Encryption involves encoding data to make it unintelligible to unauthorized users. In the context of web development, encrypting sensitive information before storing it in the database adds an extra layer of security. Tools like OpenSSL or libraries such as bcrypt.js can be used for encryption in JavaScript applications.

## Hashing and Salting with bcrypt🔐

Hashing transforms sensitive data into a fixed-size string of characters, making it challenging for attackers to reverse-engineer the original data. Salting involves adding random data (salt) to the input before hashing, further enhancing security. The bcrypt library in Node.js simplifies the process of hashing and salting passwords securely.

## Session Management with Sessions and Cookies🔏

Sessions and cookies are commonly used to persist user login sessions across multiple requests. Sessions store user-specific data on the server, while cookies store data on the client-side. Implementing session management ensures that users remain authenticated throughout their browsing session, enhancing user experience and security.

## Local Authentication Setup🧰

Setting up local authentication involves creating a custom authentication system from scratch using user credentials stored in a local database. This process includes validating user inputs, hashing and salting passwords, and managing user sessions securely.

## Using Passport.js for Authentication🧰

Passport.js is a popular authentication middleware for Node.js applications, offering a wide range of authentication strategies, including local authentication, OAuth, and more. Integrating Passport.js simplifies the authentication process and provides robust security features out of the box.

## Securing Secret Keys with Environment Variables🔑

Sensitive information such as API keys, database credentials, and cryptographic keys should never be hard-coded in the application code. Instead, they should be stored as environment variables and accessed programmatically. This practice minimizes the risk of exposing sensitive information and enhances application security.

## OAuth 2.0 Integration🔐 

OAuth 2.0 is an industry-standard protocol for authorization, allowing users to grant third-party applications limited access to their resources without sharing their credentials. Integrating OAuth 2.0 with popular identity providers such as Google and Facebook enables seamless and secure user authentication in JavaScript applications.

- [x] For detailed implementation instructions and code examples, please refer to the sample code provided in this repository.

## Screenshots 🖼️

![secrets_home](https://github.com/shanibider/Authentication-and-Security-Node-Express-PostgreSQL/assets/72359805/4a761bed-8e4a-4ca5-bb45-176b609fa6f0)

### Level 1 - Basic authentication - Registration users with email and password (password stored unencrypted in db) -
![2](https://github.com/shanibider/Authentication-and-Security-Node-Express-PostgreSQL/assets/72359805/260fdc2d-f934-4034-8586-ad1df079a832)
![3](https://github.com/shanibider/Authentication-and-Security-Node-Express-PostgreSQL/assets/72359805/1cee2680-8027-4880-aaf1-0b97d750dd1e)

### Level 2 of authentication - Encrypting and Hashing passwords -
![4-hash](https://github.com/shanibider/Authentication-and-Security-Node-Express-PostgreSQL/assets/72359805/9d4094b4-61fd-4a0c-8fd6-4d5120b51801)

### Level 3 Authentication - using OAuth (Open Authorisation, third party) to authenticate users, without storing their credentials -
![5-outh](https://github.com/shanibider/Authentication-and-Security-Node-Express-PostgreSQL/assets/72359805/921098a6-8813-4ca5-8781-f1bf9e03da2c)
![6](https://github.com/shanibider/Authentication-and-Security-Node-Express-PostgreSQL/assets/72359805/a339aa47-d82b-4798-b5bb-8d1969549d10)





## Installation 🛠️

1. Clone the repository: `git clone <this-utl>`
2. Navigate to the project directory: `cd <specific-directory>`
3. Install dependencies: `npm install`
4. Start the server: `nodemon app.js` or `npm start`
5. Open your web browser and visit `http://localhost:3000` to view the application.


> Feel free to explore my repositories and see my projects. I'm always open to collaboration and welcome feedback to improve and grow as a developer. Let's code something amazing together! 🚀😊👩‍💻💻


## 📫 Connect with me 😊
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shani-bider/)
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://shanibider.github.io/Portfolio/)
[![gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shanibider@gmail.com)

<footer>
<p style="float:left; width: 20%;">
Copyright © Shani Bider, 2024
</p>
</footer>

## License📄

This project is licensed under the MIT License.

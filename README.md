#  Support Ticket System App

Support Ticket System App is a MERN stack project designed to learn React.js, Redux (used Redux Toolkit) and combine this with a backend side of the application written using Express.js and MongoDB as the database.

The app allows the user to register (registration without having to confirm an email, more about this in the "Features" tab) and log in. Once logged in, the user can add tickets regarding broken devices. After adding a ticket, one can also add notes to a specific ticket to better communicate with the supposed technical support.

When creating an account (and logging in), I added a validation process. Also The account is added to the database (password is hashed using bcrypt.js and then saved to the database) - not only is the account added to the database, but also tickets etc. I also used a JWT with a specific expiry time and localStorage to handle the login.

## [Live Demo]

<p>Will be added in the future!</p>
<p>Moving from Heroku to another hosting website...</p>
<p>Screenshots as a preview.</p>

## Technologies Used

![javascript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![mongodb](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![react](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![react-router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![redux](https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white)

## Features

- Registration with validation and saving user to the database (real registration with email confirmation, etc., is possible to be added in the future, at the moment I preferred to focus on other aspects of the application)
- Password hashing using bcrypt.js
- Logging in using JWT (including expiry time) and saving to localStorage
- Logout with deletion of data from localStorage
- Protected routes for the backend api
- Protected routes for the frontend side of the application
- Validation and creation of tickets and saving to the database for a specific user
- Modification and deletion of tickets by specific user (in progress to implement for frontend, backend api written)
- The possibility of closing tickets completely (e.g. due to case resolution)
- Display of tickets only for the user who created them
- Adding notes via modal and saving them to the database

## Screenshots

![App Screenshot](https://thumbs2.imgbox.com/f7/81/DGIojhNb_t.png)
<br>
![App Screenshot](https://thumbs2.imgbox.com/89/38/1totzq72_t.png)
<br>
![App Screenshot](https://thumbs2.imgbox.com/30/78/w7TbOZgt_t.png)
<br>
![App Screenshot](https://thumbs2.imgbox.com/28/83/t3dL0ZFA_t.png)
<br>
![App Screenshot](https://thumbs2.imgbox.com/07/18/IgpJdV7c_t.png)
<br>
![App Screenshot](https://thumbs2.imgbox.com/c2/98/ZkQ6Yp84_t.png)
<br>
![App Screenshot](https://thumbs2.imgbox.com/34/67/Lc9UXnrm_t.png)


# Neighborhood Community Platform

A web-based platform designed to foster community interaction within neighborhoods. The platform allows users to register, log in, add stores, browse local businesses, and interact with the neighborhood community digitally.

## Features

- 🏠 Home Page with quick access to various features
- 🔐 User Registration & Login System (Node.js + MongoDB)
- 🏪 Store Management (Add, View, and Manage Stores)
- 📄 Store Details Page
- 📞 Contact and About Pages
- 🖥️ Front-end: HTML, CSS, JavaScript
- 💾 Back-end: Node.js
- 🗄️ Database: MongoDB

## Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose ODM)

## Project Structure

```

project-folder/
│
├── server.js (Main backend file)
├── package.json
├── models/
│   └── user.js (User schema)
│   └── store.js (Store schema)
├── routes/
│   └── signup.js
│   └── login.js
│   └── store.js
├── public/
│   └── (CSS, Images, JS)
├── views/
│   └── register.html
│   └── login.html
│   └── home.html
│   └── addstore.html
│   └── storedetails.html
│   └── contact.html
│   └── about.html
└── README.md

````

## Setup Instructions

1. **Clone the repository:**

```bash
git clone https://github.com/JaffySherlinA/neighborhood-community-platform.git
cd neighborhood-community-platform
````

2. **Install dependencies:**

```bash
npm install
```

3. **Configure MongoDB:**

* Ensure MongoDB is running locally or use MongoDB Atlas.
* Update MongoDB connection string inside `server.js` or use environment variables.

4. **Start the server:**

```bash
node server.js
```

5. **Access the app:**

Open your browser and go to `http://localhost:3000`

## Future Improvements

* Add authentication middleware
* Implement role-based access (admin, user)
* Store images for stores and users
* Community post or forum feature
* Better error handling & form validations
* Responsive design improvements

## Screenshots

> *Home Page*
![image](https://github.com/user-attachments/assets/726fd373-ba0b-472e-af20-0a8961e1b16b)
> *Registration Page*
![image](https://github.com/user-attachments/assets/232e8133-c28d-447a-bf63-a3208a2e6f98)
> *Login Page*
![image](https://github.com/user-attachments/assets/0dc306b2-0b4b-4af7-875d-38712a03bf8b)
> *Add New Store*
![image](https://github.com/user-attachments/assets/1277dd14-71d2-4f36-9972-2b486042a5b5)
> *Weekend Events*
![image](https://github.com/user-attachments/assets/f345b827-6b70-4596-9ca7-21d95075ad20)
> *Store & Events*
![image](https://github.com/user-attachments/assets/78f500ad-147f-4746-a9cc-907a1114271c)


## Author

* Jaffy Sherlin A — [GitHub](https://github.com/JaffySherlinA)



Role Based Access Control


In every modern web application, Role-Based Access Control (RBAC) is a key security mechanism that ensures users only have access to the data and actions that are appropriate for their role within an application.

---

## To start setting up the project

Step 1: Clone the repo

```bash
git clone https://github.com/trulymittal/role-based-access-control
```

Step 2: cd into the cloned repo and run:

```bash
npm install
```

Step 3: Put your credentials in the .env file.

```bash
PORT=3000
MONGODB_URI=YOUR_MONGODB_URI(example: mongodb://localhost:27017)
DB_NAME=YOUR_DB_NAME
```


Step 4: Install MongoDB on Windows
If you haven't already installed MongoDB, follow these steps to set it up on Windows:

Go to the MongoDB download page and choose the Windows version.
Run the installer and follow the instructions to complete the installation.
For more details, refer to the MongoDB Windows Installation Guide.

Step 5: Start MongoDB Daemon
To run MongoDB, open a new Command Prompt (CMD) window and start the MongoDB service:

net start MongoDB

Alternatively, if MongoDB is not installed as a service, use this command to manually start the MongoDB daemon:

mongod


Step 6: Start the app by

```bash
npm start
```

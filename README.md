Split App
The Expense Tracker Website is a web-based application designed to help users track their expenses efficiently. This platform aims to provide users with a convenient  way to monitor their spending habits, categorize expenses, and analyze their financial data. By offering a user-friendly interface and robust features.

![s1](https://github.com/user-attachments/assets/cb55b522-277a-4126-a467-364ac7ab310a)

![dash board](https://github.com/user-attachments/assets/b6da368b-a7f5-4b91-8fd6-217bcbe3c1d1)


In the first terminal

1.  cd client
2. npm install (to install client-side dependencies)
3. npm start (to start the client)

For setting up backend

cd create a .env file in the root of your directory.
Supply the following credentials
PORT=3001
MONGODB_URI=
ACCESS_TOKEN_SECRET=

Please follow This tutorial to create your mongoDB connection url, which you'll use as your MONGODB_URI

Provide some random key in ACCESS_TOKEN_SECRET or you could generate one using node enter the below command in the terminal to genrate a random secret key

node -e "console.log(require('crypto').randomBytes(256).toString('base64'));"


In the second terminal (*in the project root directory (back-end))

1. npm install (to install server-side dependencies)
2. npm start (to start the server)

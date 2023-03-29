# social-media-app

## How to run
- Clone the repository.
- cd into the server directory and run 
<code>npm install</code>
- Create a dotenv file in the directory and paste the following in it:
> MONGO_URL = '<YOUR_MONGODB_ATLAS_URL>'
>
> JWT_SECRET = 'some random string' 
>
> PORT = 3001
- Replace the placeholder with your own data.
- Run <code>npm start</code>. The server will run on port 3001
- In a new terminal, cd into the client directory and run <code>npm install</code>
- Once all packages are installed, run <code>npm start</code>. The frontend will run on localhost:3000.

Deployed App Guest Credentials:
- Email: guest@email.com
- Password: guest

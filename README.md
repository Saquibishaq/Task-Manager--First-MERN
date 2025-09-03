

## Technologies Used

- **Frontend:**
  - [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
  - [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS)
  - [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
  - [React.js](https://reactjs.org/)

- **Backend:**
  - [Node.js](https://nodejs.org/)
  - [Express](https://expressjs.com/)

- **Database:**
  - [MongoDB](https://www.mongodb.com/)

- **Other Tools:**
  - [Git](https://git-scm.com/)
  - [GitHub](https://github.com/)
  - [VSCode](https://code.visualstudio.com/)
    
 

To check if you have Node.js and npm installed, run the following commands in your terminal:

```bash
node --version
npm --version
```
## How To Run
Create the file `BackEnd/config.env` with your Atlas URI and the server port:

**FrontEnd**
```
REACT_APP_API_URL = your backend api with port
```
**BackEnd**
```
MONGO_URL = your mongoDb url either from atlas or from localhost shell
```
If you are going Authenticate with Facebook and Google Through PassportJs Stratgy...
```
GOOGLE_CLIENT_ID = your google app clint id
GOOGLE_CLIENT_SECRET = your google app client secret
FACEBOOK_CLIENT_ID = your facebook app clint id
FACEBOOK_CLIENT_SECRET = your facebook app client secret
FRONTEND_DOMAIN = you react app url with port
SESSION_SECRET = anything you want
JWT_SECRET_KEY = anything you want
```
Start server i.e., BackEnd:
```
cd Task-Manager--First-MERN/BackEnd
npm install
npm start
```
Start Client i.e., FrontEnd:
```
cd Task-Manager--First-MERN/FrontEnd
npm install
npm start or npm run dev
```
 

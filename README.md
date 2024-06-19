# Job Connect Application

## Project Description
Jobconnect is a final year project created by a team of four members: Joy Chakraborty, Sathi Ruidas, Priyanshu Burman, and Abhijit Shaw. This project aims to develop a job website using modern technologies, including MongoDB Atlas, React.js, Express.js, and Node.js. The project also utilizes Material-UI for CSS styling.


## Technologies Used
### Frontend
- React.js
- Material-UI (for CSS styling)
  - @material-ui/core
  - @material-ui/icons
  - @material-ui/lab
- Axios
- Material-UI Chip Input

### Backend
- Node.js
- Express.js
- MongoDB Atlas(Mongoose)
  - mongoose
- Authentication
  - bcrypt
  - jsonwebtoken
  - passport
  - passport-jwt
  - passport-local
- Middleware
  - body-parser
  - connect-flash
  - connect-mongo
  - cors
  - express-session
- File Uploads
  - multer
- Utilities
  - crypto
  - uuid

## Directory Structure
```
Job-Connect-Application
│
├── info.txt
├── PPT
│ └── Presentation on JobConnectPortal.pptx
│
├── Documents
│ ├── A Project Report on JobConnectPortal.pdf
│ └── A Project Report on JobConnectPortal.docx
│
├── Source Code
│ ├── JobConnectPortal
│ │ ├── frontend
│ │ │ ├── src
│ │ │ │ ├── components
│ │ │ │ │ ├── recruiter
│ │ │ │ ├── lib
│ │ ├── backend
│ │ │ ├── lib
│ │ │ ├── dib
│ │ │ ├── routes
│ │ │ │ ├── public
│ │ │ │ ├── profile
│ │ │ │ │ ├── resume
│ │ │ │ │ ├── profile
└── env
```

## Setup Instructions
### Prerequisites
- Node.js
- MongoDB Atlas

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/FYP/jobconnect.git
    ```

3. Navigate to the `backend` directory and install dependencies:
    ```bash
    cd backend
    npm install
    ```

4. Start the Express server:
    ```bash
    npm start
    ```
    The backend server will start on port 4444.

5. Navigate to the `frontend` directory and install dependencies:
    ```bash
    cd ../frontend
    npm install
    ```

6. Start the frontend server:
    ```bash
    npm start
    ```
    The frontend server will start on port 3000.

7. Open your browser and go to:
    ```bash
    http://localhost:3000/
    ```
    Proceed with creating jobs and applications by signing up in the required categories.

### Environment Variables
Create a `.env` file in the `backend` directory and add the following:
MONGO_URI=your_mongodb_uri


## Team Members
- [Priyanshu Burman](https://www.linkedin.com/in/priyanshu-burman-4b335828b/) (10800220058)
- [Sathi Ruidas](https://www.linkedin.com/in/sathi-ruidas-372409210/) (10800220069)
- [Abhijit Shaw](https://www.linkedin.com/in/abhijit-shaw-78077122a/) (10800220081)
- [Joy Chakraborty](https://www.linkedin.com/in/yesiamjc/) (10800220083)

## Contribution
Contributions are welcome. Please create an issue or submit a pull request for any feature requests or bug fixes.

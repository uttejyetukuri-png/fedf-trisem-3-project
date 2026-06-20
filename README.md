Project Overview

The Student Union Election Portal is a web-based voting system developed using React.js. The application provides a secure and user-friendly platform for conducting student union elections. It includes voter authentication through OTP verification, voter ID verification, face verification using a webcam, candidate selection, vote submission, and result management.

The system aims to digitize the election process, improve transparency, reduce manual effort, and ensure fair voting practices within educational institutions.

Objectives
To provide a secure online voting platform.
To authenticate voters using OTP verification.
To prevent unauthorized voting through voter ID and face verification.
To allow students to cast votes electronically.
To display election results efficiently.
To maintain voting records using local storage or database systems


Technologies Used
Frontend
React.js
JSX
HTML
CSS
JavaScript
Backend (Optional Enhancement)
Node.js
Express.js
MySQL
Browser APIs
Webcam Access (MediaDevices API)
Local Storage API

Student Union Election Portal
│
├── Dashboard
│   ├── Home Page
│   ├── Navigation Menu
│
├── Voting Module
│   ├── Mobile Number Entry
│   ├── OTP Verification
│   ├── Voter ID Verification
│   ├── Face Verification
│   ├── Candidate Selection
│   └── Vote Submission
│
├── Results Module
│   ├── Vote Counting
│   └── Result Display
│
├── Admin Panel
│   ├── View Total Votes
│   ├── Candidate Statistics
│   └── Election Monitoring
│
├── Local Storage
│   ├── Store Votes
│   └── Retrieve Vote Data
│
└── Backend (Node.js & Express)
    ├── Vote API
    ├── Result API
    └── Database Connectivity

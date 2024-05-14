# EventIQ Web Application

EventIQ is a sophisticated event management web application designed to streamline the process of planning, organizing, and managing events. This application leverages advanced features to ensure a seamless experience for both organizers and participants.

## Features

- **Event Creation and Management**: Easily create and manage events with detailed descriptions, schedules, and locations.
- **User Registration and Authentication**: Secure user registration and login system.
- **Interactive Event Calendar**: View events in an intuitive calendar format.
- **Notifications**: Stay updated with notifications about upcoming events and changes.
- **User Profiles**: Manage user profiles with personal details and event history.
- **Responsive Design**: Fully responsive design for optimal viewing on any device.

## Technologies Used

- **Frontend**: React.js, HTML5, CSS3
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **Deployment**: Heroku

## Installation

To get a local copy up and running, follow these simple steps:

### Prerequisites

- Node.js (v14 or higher)
- MongoDB (local or Atlas)

### Clone the Repository

```bash
git clone https://github.com/arman-dogru/eventiq-webapp.git
cd eventiq-webapp
```

### Install Dependencies
```bash
npm install
```

### Set Up Environment Variables
Create a .env file in the root directory and add the following variables:

```makefile
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
PORT=5000
```

### Run the Application
```bash
npm run dev
```

The application will be available at http://localhost:5000.

### Usage
- Register an Account: Sign up with your email and create a password.
- Create an Event: Fill in the event details and save.
- View Events: Browse and manage events via the interactive calendar.
- Notifications: Receive updates and reminders for your events.

### Contributing
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

- Fork the Project
- Create your Feature Branch (git checkout -b feature/AmazingFeature)
- Commit your Changes (git commit -m 'Add some AmazingFeature')
- Push to the Branch (git push origin feature/AmazingFeature)
- Open a Pull Request

### License
Distributed under the MIT License. See LICENSE for more information.

### Contact
Arman Dogru - arman.dogru@example.com

Project Link: https://github.com/arman-dogru/eventiq-webapp

### Acknowledgments

Thanks to all the contributors and users who have made this project possible.
Special thanks to the open source community for the tools and resources.
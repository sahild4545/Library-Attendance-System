# Library Attendance System
Website Link ---> https://cozy-hotteok-328d03.netlify.app/
## Overview
The **Library Attendance System** is a web application designed to manage attendance records for students visiting the library. It provides features for students to log in, record their entry and exit times, and view their attendance history. The system also includes administrative functionalities for librarians to monitor attendance, generate reports, and manage student accounts.

## Key Features
- **Student Authentication**: Students can log in using their credentials to access the system.
- **Attendance Recording**: Students can record their entry and exit times when entering or leaving the library.
- **Attendance History**: Students can view their past attendance records and statistics.
- **Admin Dashboard**: Librarians have access to an admin dashboard for managing student accounts, viewing attendance reports, and monitoring system activity.
- **Reports Generation**: Librarians can generate attendance reports for specific time periods or student groups.
- **Notifications**: Automatic notifications can be sent to students for overdue library visits or other relevant updates.
- **QR Code Integration**: QR codes can be used to facilitate quick check-ins and check-outs for students.

## Technologies Used
- **Frontend**: React.js, HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **QR Code Generation**: QR Code API
- **Data Visualization**: Chart.js
- **Notification Service**: Email or SMS API (optional)

## Installation and Setup
1. Clone the repository to your local machine:
   ```sh
   git clone https://github.com/your-repo/library-attendance-system.git
   ```
2. Navigate to the project directory:
   ```sh
   cd library-attendance-system
   ```
3. Install dependencies for both frontend and backend:
   ```sh
   npm install
   ```
4. Configure environment variables for database connection, JWT secret, and any API keys in a `.env` file.
5. Start the backend server:
   ```sh
   npm run server
   ```
6. Start the frontend development server:
   ```sh
   npm start
   ```
7. Access the application through the provided URL in your browser.

## Usage
- **Students** can log in using their credentials and record their library visits.
- **Librarians** can access the admin dashboard to manage student accounts and view attendance reports.
- Generate reports as needed for administrative purposes.
- Customize settings and features according to specific requirements.

## Contributing
Contributions are welcome! Please follow the guidelines provided in the `CONTRIBUTING.md` file. Feel free to submit issues and feature requests.

## License
This project is licensed under the MIT License.

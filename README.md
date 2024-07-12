Blood Bank Using MERN
Blood Bank is a web application developed using the MERN (MongoDB, Express.js, React, Node.js) stack. It allows users to manage blood donation activities, catering to different roles such as admin, donor, hospital, and organization.

Features
User Roles:

Admin: Manages overall system settings, user roles, and data.
Donor: Registers as a blood donor, view personal info and donation logs, and donate blood throught Organization.
Hospital: Manages blood inventory, requests blood from Organization, Tracks consumers.
Organization: Coordinates blood donation drives, manages events, and tracks donation statistics.
Authentication:

JWT (JSON Web Tokens) are used for secure authentication.
Passwords are encrypted using a bycrypt library.
Frontend:

Developed using React.js for a dynamic and responsive user interface.
State management is handled using Redux Toolkit.
Bootstrap for styling.
Backend:

Built with Node.js and Express.js, following the MVC (Model-View-Controller) architecture.
MongoDB is used as the database with Mongoose for data modeling.
Axios and Cors for handling cross origin request and responses.
Morgan and colors for error log handling.

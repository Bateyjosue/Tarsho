# Tarsho

## Overview

Tarsho is an innovative mobile application designed to connect independent contractors with customers seeking professional services. It simplifies the process of finding and engaging with reliable service providers for a range of services, including HVAC, plumbing, and electrical work. Tarsho's intuitive design and user-friendly interface are set to transform customer and service professional interactions.

![](RackMultipart20231128-1-cn3ddm_html_7472a28e29da5d7f.png)

## Key Features

- Dual Account Creation: Sign up as either a consumer or a service provider, customizing the experience to fit specific needs.
- Service Listings: Providers can list their services, including detailed information on pricing, location, and specializations.
- Proximity Search: Advanced location-based search functionality enables consumers to easily find local providers.
- User-Friendly Interface: Designed for ease of navigation to effortlessly connect users and service providers.

## Tech Stack

Tarsho employs a range of modern technologies:

- Mobile: Built with React Native for a seamless Android and iOS app experience.
- Web: Developed using React, ensuring a dynamic and responsive web platform.
- Backend: Engineered with Node.js and Express.js for robust server-side performance.
- Database: Uses MongoDB for scalable and flexible data management.
- Location Services: Integrated with Google Maps API for precise geolocation features.
- Authentication: Secured with Firebase Authentication.
- Cloud & Hosting: Deployment strategy TBD.
- CI/CD: Utilizes GitHub Actions for continuous integration and deployment.
- Version Control: Managed with Git, hosted on GitHub.

## Getting Started

### Prerequisites

- js -[Download & Install](https://nodejs.org/en/download/)
- React & React Native CLI -[Installation Guide](https://reactnative.dev/docs/environment-setup)
- MongoDB -[Download & Install](https://www.mongodb.com/try/download/community)
- Docker -[Download & Install](https://www.docker.com/products/docker-desktop)

### Installation

#### Running the Project with Docker

This method sets up the backend, frontend, and database together.

- Clone the repository:
- sh
- Copy code

git clone https://github.com/your-repo/tarsho.git

-
- Start Docker containers:
- sh
- Copy code

docker-compose up --build

-

Access the frontend at[http://localhost:3000](http://localhost:3000/) and backend APIs at[http://localhost:4000](http://localhost:4000/).

#### Development without Docker

For frontend React development:

- Navigate to the web directory and install dependencies:
- sh
- Copy code

cd web

npm install

-
- Run the React application:
- sh
- Copy code

npm start

-

#### Backend and Database Setup

- Navigate to the server directory and install dependencies:
- sh
- Copy code

cd server

npm install

-
- Start the backend server:
- sh
- Copy code

npm start

-

#### Docker Commands

- View logs:
- sh
- Copy code

docker logs [container\_name]

-
- Access container shell:
- sh
- Copy code

docker exec -it [container\_name] sh

-
- Stop containers:
- sh
- Copy code

docker-compose down

-

## Contributing

Contributions are welcome! Please read our[Contributing Guide](https://chat.openai.com/c/LINK_TO_CONTRIBUTING_GUIDE) for details on the code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the[LICENSE](https://chat.openai.com/c/LINK_TO_LICENSE) file for details.
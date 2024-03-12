# [www.calendair.net](https://www.calendair.net)

Calendair is a web-based scheduling tool designed to simplify and secure the planning of daily tasks and events. It was developed to address the need for an intuitive, flexible, and secure scheduling experience for those with constantly evolving schedules.

## Development Highlights

- **User Authentication**: The authentication process incorporates email verification, secure transmission of passwords over HTTPS, and encrypted storage in the backend. This approach was adopted to enhance security and user confidence.
- **Responsive Design**: The application's design is responsive, adapting to different screen sizes and devices. This was achieved through CSS and media queries, along with initial layouts planned using Figma.
- **Security Measures**: The backend, built with Python (Flask), employs several security measures including SSL/TLS for encrypted connections, rotating HTTPOnly JWTs for session management, and secure RESTful API endpoints. Database (SQL) encryption further protects user data.
- **Infrastructure and Deployment**: Deployment involved setting up a domain, configuring DNS forwarding, and creating an AWS Elastic Beanstalk environment. These steps, along with implementing SSL/TLS certification and configuring load balancers, were essential in handling web traffic and ensuring reliability.

## Technologies Used

The project leverages a combination of technologies to offer a seamless and secure scheduling experience:
- **Frontend**: Developed with ReactJS, the frontend emphasizes usability and responsiveness, ensuring that users can efficiently manage their schedules on any device.
- **Backend**: The Flask-based backend focuses on security and performance, with careful attention to protecting user data and interactions.
- **Deployment**: AWS services, including Elastic Beanstalk and load balancers, provide a scalable and secure hosting environment, ensuring that Calendair remains accessible and responsive.

## Project Motivation

Calendair was born out of a desire to create a scheduling tool that not only meets the practical needs of users but also addresses security and privacy concerns inherent in online scheduling. The development process was marked by a commitment to learning and implementing best practices in web development, security, and user experience design.

## Exploring Calendair

While the codebase is not currently open for public review to protect user data and privacy, interested individuals are encouraged to visit [calendair.net](https://www.calendair.net) to experience the application firsthand.

For future updates or potential collaboration opportunities, please keep an eye on this repository.

## Feedback

Feedback on the project, especially regarding its development approach, technology stack, and security practices, is highly valued. Feel free to make an account to test the website, and reach out with any comments or inquiries.

I appreciate your interest in Calendair and its development journey. More to come!

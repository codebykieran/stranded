# Stranded

## Overview
Stranded is a quality-of-life application designed to streamline the often stressful experience of getting or completing a haircut. Both barbers and clients can register to use the service, making the process of booking, managing, and completing haircuts more efficient and enjoyable for everyone involved.

## Motivation
Getting a haircut or managing appointments as a barber can be unnecessarily complicated and stressful. Stranded aims to simplify this process by providing a dedicated platform that addresses the unique needs of both barbers and clients, reducing friction and improving the overall experience.

## Features
Stranded is essentially split into two sides: one for barbers and one for customers. Key features include:

Application Wide:
- Profile creation and management
- Secure authentication and data handling
- Responsive mobile-first design
- Calendar Functionality for appointment planning, leaving notes etc.
- Chat system; communication bewteen barbers and clients.

Barber Specific:
- Learning portal 
- Personal Journal 
- Ability to block troublesome clients
- Events section? Potential to add posts when models are needed for shows, social media pushes etc.

Client Specific:

- Area for learning terminology, commmon hair misconceptions, etiquette 
- Ability to leave ratings and reviews for barbers
- Search and filter barbers by location, specialty, and availability


## Tech Stack
- Frontend: React Native
- Backend: Node.js with Express
- Database: MongoDB
- Authentication: JWT
- Styling: Tailwind CSS
- Deployment:
    Local Setup: localhost
    Live Seyup: Heroku server

## Additional Tech Suggestions
Based on the context, you may also consider:
- Push notifications: Firebase Cloud Messaging or Expo Notifications
- Real-time updates: Socket.io for live appointment status
- Maps/location: Google Maps API or Mapbox for finding nearby barbers
- Payments: Stripe or PayPal integration for in-app payments
- Deployment: Docker for containerization, AWS/GCP/Azure for hosting

## License
MIT License

---

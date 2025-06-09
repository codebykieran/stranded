# Stranded

## Overview
Stranded is a quality-of-life application designed to streamline the often stressful experience of getting or completing a haircut. Both barbers and clients can register to use the service, making the process of booking, managing, and completing haircuts more efficient and enjoyable for everyone involved.

## Motivation
Getting a haircut or managing appointments as a barber can be unnecessarily complicated and stressful. Stranded aims to simplify this process by providing a dedicated platform that addresses the unique needs of both barbers and clients, reducing friction and improving the overall experience.

## Features
Stranded is essentially split into two sides: one for barbers and one for customers. Key features include:

- User registration for both barbers and clients
- Barber profile creation and management
- Customer profile creation and management
- Calendar view for barbers and clients
- Chat system with barbers. Both barbers and clients are able to attach images for inspiration prior to appointment.
- Section to learn popular terminology for certain styles/haircuts/ styling tips, common misconceptions etc.
- Notifications for upcoming appointments and changes
- Ratings and reviews for barbers
- Search and filter barbers by location, specialty, and availability
- Secure authentication and data handling
- Responsive mobile-first design

## Tech Stack
- Frontend: React Native
- Backend: Node.js with Express
- Database: MongoDB
- Authentication: JWT
- Styling: Tailwind CSS

## Additional Tech Suggestions
Based on the context, you may also consider:
- Push notifications: Firebase Cloud Messaging or Expo Notifications
- Real-time updates: Socket.io for live appointment status
- Maps/location: Google Maps API or Mapbox for finding nearby barbers
- Payments: Stripe or PayPal integration for in-app payments
- Deployment: Docker for containerization, AWS/GCP/Azure for hosting

## Testing

the app should be testable both locally through localhost as well as on a live server, preferably using a service like Heroku.


## Roadmap
- MVP: User registration, profile management, basic appointment booking
- v1.0: Calendar view, notifications, ratings/reviews, search/filter
- v2.0: Real-time updates, payments, advanced analytics

## License
MIT License

---

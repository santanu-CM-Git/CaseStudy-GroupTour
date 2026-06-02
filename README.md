# Group Tour Case Study

## Project Name:
Group Tour

## Project Overview:
Group Tour is a global travel platform designed to help users discover affordable group tour packages from verified travel agencies worldwide. The platform connects travelers with curated group trips that reduce travel expenses through shared costs while creating opportunities to meet like-minded people and build memorable experiences.

The ecosystem consists of two dedicated applications:

- **User App** – for travelers to discover, book, and manage group tours.
- **Agency App** – for travel agencies to create, manage, and promote tour packages.

The mission of Group Tour is to make travel more accessible, social, and affordable through technology-driven experiences.

## Client:
Confidential

## Problem:
The client needed a travel ecosystem that could solve multiple challenges:

- Difficulty in finding affordable group travel options
- Lack of a centralized platform connecting travelers with verified agencies
- Complex booking workflows
- Challenges in managing travel packages and bookings for agencies
- Need for personalized travel recommendations
- Real-time synchronization of booking and trip information
- Scalability concerns for handling large travel datasets and global users

## Technology I Use:

### Frontend
- React Native
- Redux / Context API

### Backend
- Laravel
- MySQL
- REST APIs

### Payment Gateway
- Razorpay (split payment)

### Cloud Infrastructure
- AWS EC2
- AWS S3

### Notifications
- Firebase Cloud Messaging (FCM)

### Authentication
- Email Authentication

### Analytics
- Firebase Analytics

## Solution:

Designed and developed a complete travel ecosystem consisting of separate applications for travelers and travel agencies.

### User Application Features

Users can:

- Browse and discover group tour packages
- Search tours by destination and preferences
- View package details and pricing
- Book travel packages
- Track upcoming and completed trips
- Manage profile information
- View booking history

### Agency Application Features

Travel agencies can:

- Create and publish tour packages
- Manage destinations and pricing
- View customer bookings
- Manage package availability
- Track business activity
- Update travel schedules

### Tour Discovery & Personalization

Implemented:

- Global travel destination discovery
- Trending tour listings
- Verified agency listings
- Personalized travel recommendations based on:
  - Travel preferences
  - Previous bookings
  - User interests
  - Popular destinations

### Booking Management

Implemented:

- Package reservation workflow
- Booking status tracking
- Upcoming trip management
- Cancellation management

### Notifications & Engagement

Implemented notifications for:

- Booking confirmations
- Trip reminders
- Tour updates
- Promotional offers

### Analytics Tracking

Implemented Firebase Analytics for:

#### User Activity
- User registration completed
- Login completed
- Destination searched
- Tour package viewed
- Tour booked

#### Agency Activity
- Package created
- Package updated
- Booking accepted
- Tour completed

#### Booking Activity
- Booking initiated
- Booking confirmed
- Payment completed
- Trip cancelled

## Result:

- Improved accessibility to affordable travel experiences
- Increased user engagement through personalized recommendations
- Simplified travel package discovery and booking workflows
- Improved operational efficiency for travel agencies
- Better booking synchronization and real-time updates
- Supported increasing users and expanding travel inventory without performance issues
- Delivered a scalable travel ecosystem for both travelers and agencies

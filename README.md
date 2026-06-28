# Pickleball Court Booking System

A modern Astro + React + Tailwind CSS web application for managing pickleball court bookings and open play sessions.

## Features

- 🎾 **Court Management** - Add and manage pickleball courts
- 📅 **Court Booking** - Book specific courts for specific times
- 👥 **Open Play Sessions** - Schedule and join casual play sessions
- ⚡ **Real-time Updates** - Live availability checking
- 📱 **Responsive Design** - Works on desktop, tablet, and mobile

## Tech Stack

- **Framework**: [Astro](https://astro.build)
- **UI Library**: [React](https://react.dev)
- **Styling**: [Tailwind CSS](https://tailwindcss.com)
- **Build Tool**: Vite

## Getting Started

### Prerequisites

- Node.js 16+
- npm

### Installation

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

The site will be available at `http://localhost:3000`

## Backend API

Make sure you have the backend server running on `http://localhost:5000`. See the backend documentation for setup instructions.

## Project Structure

```
src/
├── components/
│   ├── BookingApp.jsx        # Main app component
│   ├── CourtsList.jsx         # Courts display and add form
│   ├── BookingForm.jsx        # Court booking interface
│   ├── OpenPlaySessions.jsx  # Open play management
│   └── Alert.jsx             # Alert notification component
├── layouts/
│   └── Layout.astro          # Main layout
└── pages/
    └── index.astro           # Home page
```

## Usage

### Add a Court
1. Go to the "Courts" tab
2. Fill in court details (name, location, surface, lights)
3. Click "Add Court"

### Book a Court
1. Go to the "Book Court" tab
2. Select a court and date
3. Choose start and end times
4. Enter your details
5. Click "Book Now"

### Join Open Play
1. Go to the "Open Play" tab
2. View available sessions or schedule a new one
3. Click "Join Session" and enter your details

## Future Enhancements

- User authentication
- Payment integration
- Email notifications
- Admin dashboard
- Calendar integration
- Ratings and reviews
- Mobile app

## License

MIT

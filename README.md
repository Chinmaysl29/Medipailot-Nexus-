# MediPilot Nexus - Healthcare Platform

A comprehensive healthcare platform designed to streamline interactions between patients, hospitals, and insurance providers.

## Features

### Patient Interface
- **Medical Reports**: Upload and view medical reports with AI-powered analysis
- **Appointments**: Request and manage appointments with hospitals
- **Medications**: Track medications with reminders and schedules
- **Health Metrics**: Monitor vital health metrics (blood pressure, blood sugar, etc.)
- **Meal Plans**: Generate AI-powered personalized meal plans

### Hospital Interface
- **Appointment Requests**: View and manage patient appointment requests
- **Slot Management**: Create and manage available appointment slots
- **Patient Management**: Coordinate patient care

### Insurance Interface
- **Claims Processing**: Review and process insurance claims
- **Coverage Verification**: Verify patient coverage and policy details
- **Pre-Authorization**: Manage pre-authorization requests

## Technology Stack

- **Frontend**: React 18, Vite
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Routing**: React Router DOM
- **State Management**: TanStack Query
- **Database**: In-memory database (simulated)

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Open your browser and navigate to `http://localhost:3000`

### Demo Accounts

The application comes with three pre-configured demo accounts:

**Patient Account:**
- Email: `patient@demo.com`
- Password: `demo123`

**Hospital Account:**
- Email: `hospital@demo.com`
- Password: `demo123`

**Insurance Account:**
- Email: `insurance@demo.com`
- Password: `demo123`

## Project Structure

```
medipilot-nexus/
├── src/
│   ├── components/          # Reusable components
│   │   ├── BottomNav.jsx
│   │   ├── Card.jsx
│   │   └── Layout.jsx
│   ├── hooks/              # Custom React hooks
│   │   └── useAuth.js
│   ├── pages/              # Page components
│   │   ├── patient/        # Patient interface pages
│   │   ├── hospital/       # Hospital interface pages
│   │   ├── insurance/      # Insurance interface pages
│   │   ├── Home.jsx
│   │   ├── Login.jsx
│   │   └── InterfaceSwitcher.jsx
│   ├── services/           # Business logic and services
│   │   ├── database.js     # In-memory database
│   │   └── aiService.js    # AI simulation services
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── index.html
├── package.json
├── vite.config.js
├── tailwind.config.js
└── postcss.config.js
```

## Key Features

### AI Integration
- **Report Analysis**: Automatically analyzes uploaded medical reports
- **Auto-Appointment Booking**: AI agent initiates appointment booking based on analysis
- **Diet Plan Generation**: Creates personalized meal plans based on health goals

### User Experience
- **Interface Switching**: Easy switching between patient, hospital, and insurance interfaces
- **Responsive Design**: Works seamlessly on mobile and desktop devices
- **Smooth Animations**: Framer Motion for fluid transitions
- **Bottom Navigation**: Quick access to key features

### Data Management
- User profiles with preferred interface settings
- Medical reports with AI analysis
- Appointment requests and confirmed appointments
- Medication tracking
- Health metrics monitoring
- Meal plans
- Insurance claims and policies

## Building for Production

```bash
npm run build
```

The built files will be in the `dist` directory.

## Preview Production Build

```bash
npm run preview
```

## Future Enhancements

- Real backend integration with Base44 platform
- Real-time notifications
- Video consultations
- Prescription management
- Lab test integration
- Payment processing
- Multi-language support
- Advanced analytics dashboard

## License

MIT License

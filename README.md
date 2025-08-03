# FITZ - Complete Health & Fitness Platform

A comprehensive health and fitness platform with AI-powered assistance, doctor consultations, and personalized wellness tracking.

## Features

### 🏥 Health & Wellness
- **Health Tracking**: Monitor vital signs, symptoms, and health metrics
- **BMI Calculator**: Calculate and track your Body Mass Index
- **Calorie Tracker**: Monitor daily nutrition and calorie intake
- **Medical Records**: Secure storage and management of health documents

### 💪 Fitness & Exercise
- **Personalized Workouts**: Custom exercise plans based on your goals
- **Fitness Tracking**: Monitor progress and achievements
- **Exercise Library**: Access to various workout routines

### 👨‍⚕️ Healthcare Services
- **Doctor Consultations**: Virtual appointments with certified healthcare professionals
- **Appointment Booking**: Easy scheduling system for medical visits
- **Health Chat**: Real-time messaging with healthcare providers
- **Doctor Registration**: Platform for healthcare professionals to join

### 🤖 AI-Powered Features
- **AI Health Assistant**: Advanced AI chatbot for health guidance
- **Voice Recognition**: Voice-enabled interactions
- **Personalized Recommendations**: AI-driven health and fitness advice

### 🔐 Security & Privacy
- **Secure Authentication**: Protected user accounts and data
- **Privacy Protection**: Enterprise-grade security measures
- **Role-based Access**: Different access levels for users, doctors, and administrators

## Technology Stack

- **Frontend**: React 18 with TypeScript
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Build Tool**: Vite
- **AI Integration**: OpenAI API
- **Real-time Communication**: Socket.io

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd fitz-health-app
```

2. Install dependencies:
```bash
npm install
```

3. Create environment variables:
```bash
cp .env.example .env
```

4. Configure your environment variables:
```env
VITE_OPENAI_API_KEY=your_openai_api_key
VITE_MONGODB_URI=your_mongodb_connection_string
VITE_SOCKET_URL=your_socket_server_url
```

5. Start the development server:
```bash
npm run dev
```

6. Open your browser and navigate to `http://localhost:5173`

## Demo Accounts

For testing purposes, you can use these demo accounts:

- **User**: user@test.com / password
- **Doctor**: doctor@test.com / password
- **Owner**: fitzowner@fitz.com / nextus

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Project Structure

```
src/
├── components/          # Reusable UI components
├── contexts/           # React contexts (Auth, etc.)
├── lib/               # Utility libraries and services
├── pages/             # Page components
├── types/             # TypeScript type definitions
├── App.tsx            # Main app component
└── main.tsx           # Application entry point
```

## Key Features

### User Dashboard
- Health metrics tracking
- Fitness progress monitoring
- Appointment management
- AI chat assistance

### Doctor Dashboard
- Patient management
- Appointment scheduling
- Medical record access
- Consultation tools

### Owner Dashboard
- Platform administration
- User management
- Doctor approval system
- Analytics and reporting

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## License

This project is licensed under the MIT License.

## Support

For support and questions, please contact the development team.

---

**FITZ** - Your complete health and fitness companion with AI-powered assistance and comprehensive wellness tracking. 
# Aarogya Setu Gram - Rural Healthcare Platform

[![Build Status](https://github.com/Shakil123hq/aarogya-setu-gram/workflows/CI%2FCD/badge.svg)](https://github.com/Shakil123hq/aarogya-setu-gram/actions)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-0.0.0-green.svg)](package.json)
[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen.svg)](https://aarogya-setu-gram.vercel.app/)

> 🏥 **Empowering rural healthcare through technology** - A modern React-based healthcare management platform for rural communities in India, connecting patients with ASHA workers and providing comprehensive health monitoring tools.

## 🌟 Overview

**Aarogya Setu Gram** is a comprehensive, multilingual healthcare platform built with modern web technologies, specifically designed for rural communities in India. The platform bridges the healthcare gap by connecting patients with ASHA (Accredited Social Health Activist) workers and providing essential tools for chronic disease management and health monitoring.

### ✨ **Modern React Architecture**

Our platform features a **professional, responsive UI/UX** built with cutting-edge technologies:

- ⚛️ **React 18 + TypeScript**: Modern component-based architecture with type safety
- 🎨 **Tailwind CSS + shadcn/ui**: Beautiful, accessible UI components
- 🚀 **Vite**: Lightning-fast development and build process
- 📱 **Responsive Design**: Seamless experience across all devices
- 🌐 **React Router**: Smooth client-side navigation

### 🎯 Core Features

- **📱 Multilingual Support**: Available in Hindi, English, and Marathi
- **🏥 Health Vitals Tracking**: Blood pressure, blood sugar, weight monitoring with trend analysis
- **👩‍⚕️ ASHA Worker Integration**: Direct connection with local health workers
- **📊 Patient Dashboard**: Comprehensive health overview and progress tracking
- **💊 Medication Management**: Smart reminders and prescription tracking
- **📅 Appointment Scheduling**: Easy booking and management system
- **📈 Health Reports**: Detailed analytics and health insights
- **🔒 Secure Authentication**: Mock authentication system for development
- **📱 Progressive Web App**: App-like experience on mobile devices

## 🏛️ Professional Healthcare Interface

### 🎨 Design Highlights

- **Modern Healthcare UI**: Clean, professional interface designed for healthcare workflows
- **Component-Based Architecture**: Reusable UI components using shadcn/ui and Radix UI
- **Accessibility First**: WCAG compliant design with proper keyboard navigation and screen reader support
- **Multi-Dashboard System**: Separate interfaces for patients and health workers
- **Form Validation**: Comprehensive form validation using React Hook Form and Zod
- **Real-time Updates**: Dynamic data updates using TanStack Query

### 📱 User Experience

- **Role-Based Dashboards**: Customized interfaces for patients and ASHA workers
- **Intuitive Navigation**: Clear menu structure with React Router navigation
- **Interactive Charts**: Health data visualization using Recharts
- **Toast Notifications**: Real-time feedback using Sonner and shadcn/ui toasts
- **Mobile-First Design**: Optimized for mobile devices commonly used in rural areas

## 🚀 Quick Start & Development

### Prerequisites

- **Node.js 16+** and npm
- **Modern web browser**
- **Git** for version control

### 🔧 Development Setup

```bash
# Clone the repository
git clone https://github.com/Shakil123hq/aarogya-setu-gram.git
cd aarogya-setu-gram

# Install dependencies
npm install

# Start development server
npm run dev

# Access at http://localhost:8080
```

### 🏗️ Build for Production

```bash
# Build for production
npm run build

# Preview production build
npm run preview

# Lint code
npm run lint
```

## 🛠️ Technology Stack

### Frontend Framework

- **React 18.3.1** - Modern React with hooks and concurrent features
- **TypeScript 5.8.3** - Type-safe JavaScript development
- **Vite 5.4.19** - Next-generation frontend tooling

### UI Framework & Styling

- **Tailwind CSS 3.4.17** - Utility-first CSS framework
- **shadcn/ui** - High-quality React components built on Radix UI
- **Radix UI** - Low-level accessible UI primitives
- **Lucide React** - Beautiful & consistent icon library
- **React Icons** - Popular icon libraries for React

### State Management & Data Fetching

- **TanStack Query 5.83.0** - Powerful data synchronization for React
- **React Hook Form 7.61.1** - Performant forms with easy validation
- **Zod 3.25.76** - TypeScript-first schema validation

### Routing & Navigation

- **React Router DOM 6.30.1** - Declarative routing for React applications

### Charts & Data Visualization

- **Recharts 2.15.4** - Composable charting library for React

### Authentication & Backend Integration

- **Firebase 12.3.0** - Backend services and authentication
- **Mock Authentication System** - Development-friendly auth system

### Development Tools

- **ESLint** - Code linting and formatting
- **TypeScript ESLint** - TypeScript-specific linting rules
- **Vite SWC Plugin** - Fast Rust-based compilation

## 📁 Project Structure

```
aarogya-setu-gram/
├── public/                     # Static assets
│   ├── favicon.ico            # App favicon
│   ├── favicon.png            # PNG favicon
│   ├── placeholder.svg        # Placeholder images
│   └── robots.txt            # Search engine configuration
├── src/
│   ├── components/           # Reusable UI components
│   │   ├── ui/              # shadcn/ui components
│   │   ├── DepartmentsSection.tsx
│   │   ├── FeaturesGrid.tsx
│   │   ├── Header.tsx
│   │   ├── Footer.tsx
│   │   ├── Layout.tsx
│   │   └── ...
│   ├── pages/               # Application pages
│   │   ├── Index.tsx        # Landing page
│   │   ├── PatientDashboard.tsx
│   │   ├── HealthWorkerDashboard.tsx
│   │   ├── LoginPage.tsx
│   │   ├── MyHealthPage.tsx
│   │   ├── AppointmentsPage.tsx
│   │   └── ...
│   ├── hooks/               # Custom React hooks
│   │   ├── useAuth.tsx      # Authentication logic
│   │   ├── useHealthData.tsx # Health data management
│   │   ├── useLanguage.tsx  # Internationalization
│   │   └── ...
│   ├── lib/                 # Utility libraries
│   │   ├── firebase.ts      # Firebase configuration
│   │   ├── utils.ts         # Common utilities
│   │   ├── validations.ts   # Form validation schemas
│   │   └── ...
│   ├── localization/        # Language files
│   │   ├── en.json         # English translations
│   │   ├── hi.json         # Hindi translations
│   │   └── mr.json         # Marathi translations
│   ├── assets/             # Images and media files
│   ├── App.tsx             # Main application component
│   ├── main.tsx            # Application entry point
│   └── index.css           # Global styles
├── package.json            # Project dependencies and scripts
├── vite.config.ts          # Vite configuration
├── tailwind.config.ts      # Tailwind CSS configuration
├── tsconfig.json           # TypeScript configuration
└── README.md              # This file
```

## 🌐 Application Pages & Features

### 🏠 Landing Page (Index)

- **Hero Section**: Compelling introduction to the platform
- **Features Grid**: Key platform capabilities showcase
- **Departments Section**: Healthcare departments overview
- **News Section**: Latest health updates and announcements

### 👤 Patient Portal

- **Dashboard**: Personal health overview with key metrics
- **My Health**: Comprehensive health data and vitals tracking
- **Appointments**: Schedule and manage healthcare appointments
- **Medications**: Track prescriptions and medication schedules
- **Reports**: View and download health reports and test results

### 👩‍⚕️ Health Worker Portal

- **Dashboard**: ASHA worker interface with patient overview
- **My Patients**: Manage assigned patients and their health data
- **Consultations**: Conduct and record patient consultations
- **District Reach**: Track coverage area and patient distribution

### 🔐 Authentication & Registration

- **Login System**: Secure user authentication
- **Patient Registration**: Comprehensive patient onboarding
- **Health Worker Registration**: ASHA worker account creation

### 📱 Additional Features

- **Help & Support**: User assistance and documentation
- **Multilingual Interface**: Language selection and localization
- **Responsive Design**: Mobile-optimized interface

## 🎯 Development Scripts

```bash
# Development
npm run dev          # Start development server (localhost:8080)
npm run build        # Build for production
npm run build:dev    # Build in development mode
npm run preview      # Preview production build
npm run lint         # Run ESLint code analysis
```

## 🌍 Multilingual Support

The platform currently supports:

- **English** - Primary language
- **Hindi** (हिंदी) - National language support
- **Marathi** (मराठी) - Regional language support

_Additional Indian languages can be added by extending the localization system._

## 🔧 Configuration Files

- **`vite.config.ts`**: Vite build configuration with SWC plugin
- **`tailwind.config.ts`**: Tailwind CSS customization
- **`tsconfig.json`**: TypeScript compiler configuration
- **`components.json`**: shadcn/ui component configuration
- **`postcss.config.js`**: PostCSS configuration for Tailwind

## 🚀 Deployment Options

### Vercel (Recommended)

```bash
# Deploy to Vercel
vercel --prod
```

### Netlify

```bash
# Build and deploy to Netlify
npm run build
# Upload dist/ folder to Netlify
```

### Traditional Web Hosting

```bash
# Build production bundle
npm run build
# Upload dist/ folder to your web server
```

## 🎯 Target Audience

- **Primary**: Rural communities in India with limited healthcare access
- **Secondary**: ASHA workers and community health volunteers
- **Tertiary**: Government health departments and healthcare NGOs
- **Quaternary**: Healthcare administrators and policy makers

## 🤝 Contributing

We welcome contributions from developers, healthcare professionals, and rural health advocates:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Make your changes** with proper TypeScript types
4. **Run linting** (`npm run lint`)
5. **Test your changes** thoroughly
6. **Commit your changes** (`git commit -m 'Add amazing feature'`)
7. **Push to the branch** (`git push origin feature/amazing-feature`)
8. **Open a Pull Request**

### Development Guidelines

- Follow TypeScript best practices
- Use existing component patterns from shadcn/ui
- Ensure responsive design works on mobile devices
- Add proper accessibility attributes
- Include proper error handling
- Write meaningful commit messages

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support & Issues

- **GitHub Issues**: [Create an issue](https://github.com/Shakil123hq/aarogya-setu-gram/issues)
- **Discussions**: Use GitHub Discussions for questions and ideas
- **Email Support**: support@aarogyasetugram.in

## 🙏 Acknowledgments

- **ASHA Workers**: For their tireless dedication to rural healthcare
- **Government of India**: For healthcare initiatives and Digital India program
- **Rural Communities**: For inspiration and valuable feedback
- **Open Source Community**: For amazing tools and libraries
- **shadcn/ui**: For beautiful, accessible UI components
- **Tailwind CSS**: For rapid UI development capabilities

## 🔄 Version History

- **v0.0.0** - Initial development version with core features
- **Current**: Active development with modern React stack

---

**Made with ❤️ and ⚛️ for rural India's healthcare transformation**

_Bridging the digital healthcare divide, one village at a time._

## 🚀 Getting Started Today

Ready to contribute to rural healthcare? Here's how to get started:

```bash
git clone https://github.com/Shakil123hq/aarogya-setu-gram.git
cd aarogya-setu-gram
npm install
npm run dev
```

Visit `http://localhost:8080` and start making a difference! 🌟

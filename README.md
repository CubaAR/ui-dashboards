<p align="center">
   <a href="https://cuba-ui-dashboard.netlify.app/" target="_blank">
      <img src="https://shadcndashboard-demo.vercel.app/images/logos/logoicon.svg" alt="shadcndashboard-logo" width="50px" height="50px">
   </a>
</p>

<h1 align="center">
   <a href="https://cuba-ui-dashboard.netlify.app/" target="_blank" align="center">
      UI Dashboards
   </a>
</h1>

<p align="start">Shadcn Dashboard is a modern, responsive admin dashboard template built with React (Vite). Built with Shadcn UI, Base UI and Tailwind CSS v4, it ships with a modern dashboard, Blog, Notes & Tickets apps, authentication pages, form layouts, data tables, user profile, and rich UI components - giving you everything you need to build your next admin panel faster.</p>

<kbd>[![Shadcn Dashboard - Demo Screenshot](https://shadcndashboard-demo.vercel.app/OG-Image.png)](https://cuba-ui-dashboard.netlify.app/)</kbd>

## Introduction 📊

This project was developed to enhance my UI/UX engineering skills by building and customizing a modern, responsive dashboard application. It provided hands-on experience in designing reusable components, responsive layouts, interactive interfaces, form validation, data tables, authentication flows, and modern design systems using shadcn/ui.

## Key Features ✨

- **Modern Dashboard** - Ready-to-use dashboard layout with statistics, charts, and widgets
- **Apps** - Blog, Notes, and Tickets apps out of the box
- **Authentication Pages** - Login, Register, Forgot Password, OTP Verification, Reset Password, Two-Factor Auth
- **Forms & Tables** - Vertical & Horizontal form layouts and a data table
- **User Profile** - Rich profile page with connections and activity views
- **Built with React 19 + Vite** - Modern, fast, and SEO-friendly
- **Tailwind CSS v4** - Easy theming and utility-based styling
- **Responsive & Mobile-First** - Designed to look great on all devices
- **Dark Mode Support** - Full light/dark theme toggle via a custom `ThemeProvider`/`useTheme` context
- **Rich Charting** - Recharts integration for beautiful visualizations
- **Rich Text Editor** - TipTap-powered editor for the Blog app

## Folder Structure

```
|-- public/                                    # Static assets served from the site root
|-- src/                                       # Application source code
|   |-- App.tsx                                # Root application component
|   |-- main.tsx                               # Application entry point
|   |-- api/                                   # API service layer and handlers
|   |-- assets/                                # Local SVGs, images, and static helpers
|   |-- components/                            # Shared React components
|   |-- context/                               # React context providers
|   |-- css/                                   # Global and component-level CSS
|   |-- hooks/                                 # Reusable client hooks
|   |-- layouts/                               # Dashboard shell layouts (Sidebar + Header)
|   |-- lib/                                   # General utilities and helpers
|   |-- routes/                                # React Router route definitions
|   |   |-- Router.tsx                         # Central route configuration
|   |-- types/                                 # Shared TypeScript interfaces and types
|   |-- utils/                                 # Feature-specific helper functions
|   |-- views/                                 # Page-level UI composed by route files
|   |   |-- apps/                              # App view modules
|   |   |   |-- blog/                          # Blog app views
|   |   |   |-- notes/                         # Notes app views
|   |   |   |-- tickets/                       # Tickets app views
|   |   |-- auth/                              # Auth page views
|   |   |   |-- auth2/                         # Two-factor auth views
|   |   |   |-- authforms/                     # Login, Register, etc. views
|   |   |   |-- error/                         # Error page views
|   |   |   |-- maintenance/                   # Maintenance page views
|   |   |-- dashboards/                        # Dashboard charts, statistics, and widgets
|   |   |   |-- modern/                        # Modern dashboard view
|   |   |-- icons/                             # Icon showcase views
|   |   |-- pages/                             # Inner page views
|   |   |   |-- form/                          # Form layout and validation views
|   |   |   |-- tables/                        # Data table views
|   |   |   |-- user-profile/                  # User profile views
|   |   |-- spinner/                           # Loading spinner views
|-- components.json                            # shadcn/ui aliases and registry config
|-- index.html                                 # HTML entry point
|-- vite.config.ts                             # Vite configuration
|-- package.json                               # Scripts and dependencies
|-- postcss.config.js                          # Tailwind CSS v4 PostCSS setup
|-- tsconfig.json                              # TypeScript compiler and path aliases
```

**Key UI Sections**

- **Dashboard** - Modern overview with statistics, charts, and widgets
- **Apps** - Blog, Notes, and Tickets management
- **Authentication** - Login, Register, and account recovery flows
- **Forms & Tables** - Layouts, validation, and data table views
- **User Pages** - Profile page with connections and activity

---

## What's Included 📦

- Dashboard
  - Modern Dashboard
- Apps
  - Blog
  - Notes
  - Tickets
- Pages
  - User Profile
  - Form Layouts
  - Data Table
- Authentication
  - Login Page
  - Register Page
  - Forgot Password Page
  - OTP Verification Page
  - Reset Password Page
  - Two Steps Verification Page
  - Error Page
  - Maintenance Page
- Components
  - Shadcn UI Primitives
  - Recharts
  - TipTap Rich Text Editor
  - Data Tables
  - Date Pickers & Calendar
  - File Dropzone
  - OTP Input
- Miscellaneous
  - Icons Showcase
  - Dark / Light Mode

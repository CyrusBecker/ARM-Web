# ARM Admin Dashboard

This is a web application for managing academic resources, faculty schedules, curriculum, and room reservations.

**Live Website:** [https://arm-web-app.vercel.app/](https://arm-web-sti.vercel.app)

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/CyrusBecker/ARM-Web.git
   cd ARM-webApp
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   - Copy `.env.example` to `.env` and fill in your Firebase credentials.
4. Start the development server:
   ```bash
   npm run dev
   ```

## Environment Variables

Create a `.env` file in the root directory with the following:

```
VITE_FIREBASE_API_KEY=your_api_key_here
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain_here
VITE_FIREBASE_PROJECT_ID=your_project_id_here
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket_here
VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id_here
VITE_FIREBASE_APP_ID=your_app_id_here
```

## Features

- Role-based login for Academic Head and Program Head
- Manage curriculum, faculty, schedules, and room reservations
- Real-time updates with Firebase Firestore

## Tech Stack

- React 19
- Vite 7
- Firebase Firestore
- React Router

---

For any issues, please contact the project maintainer.

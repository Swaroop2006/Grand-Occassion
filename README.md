Grand Occasion 🎉

Grand Occasion is a premium event booking and management platform for banquet halls and event venues. It allows users to browse venues, check availability, upload documents, make secure payments, and manage bookings easily.

✨ Features
🎪 Browse and book banquet halls
📅 Real-time availability checking
📄 Document upload and verification
💳 Secure payment integration
👥 Multi-level admin approval system
📊 Booking management dashboard
🔐 Authentication with role-based access
🛠️ Tech Stack
Frontend
React 18
TypeScript
Vite
Tailwind CSS
shadcn/ui
Backend
Supabase
PostgreSQL Database
Authentication
Additional Tools
React Router v6
TanStack Query (React Query)
date-fns
📂 Project Structure
src/
├── components/
│   ├── admin/
│   ├── booking/
│   ├── customer/
│   └── ui/
├── contexts/
├── hooks/
├── integrations/
├── lib/
└── pages/
👨‍💼 Admin Roles
Role	Responsibilities
Admin1	Document Verification
Admin2	Availability & Payment Management
Admin3	Final Booking Approval
Super Admin	Full System Management
🚀 Getting Started
Prerequisites

Make sure you have:

Node.js 18+
npm
Supabase account
⚙️ Installation
# Clone the repository
git clone <YOUR_GITHUB_REPO_URL>

# Navigate to the project folder
cd grand-occasion

# Install dependencies
npm install

# Start development server
npm run dev

The app will run at:

http://localhost:8080
📜 Available Scripts
npm run dev       # Start development server
npm run build     # Build for production
npm run preview   # Preview production build
npm run lint      # Run ESLint
npm run test      # Run tests
🌐 Deployment

You can deploy the project using:

Vercel
Netlify
AWS Amplify
Azure Static Web Apps
🔒 Authentication & Security
Secure login/signup using Supabase Auth
Role-based access control
Protected admin routes
Secure booking workflow

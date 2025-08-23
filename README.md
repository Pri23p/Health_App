# Healthcare Management System

A modern web application for managing patient appointments and healthcare services, built with Next.js and TypeScript.

## 🛠️ Tech Stack

- **Next.js 14** - React framework with server-side rendering
- **TypeScript** - Type-safe JavaScript
- **TailwindCSS** - Utility-first CSS framework
- **Appwrite** - Backend and database service
- **Twilio** - SMS notifications

## ✨ Key Features

### For Patients:
- Patient registration and profile creation
- Appointment booking with doctors
- SMS confirmation notifications
- Mobile-responsive design

### For Admins:
- View all patient registrations
- Manage appointments (confirm, schedule, cancel)
- Dashboard with appointment statistics
- Admin authentication system

## 🚀 Getting Started

### Prerequisites:
- Node.js (version 18 or higher)
- Git
- Appwrite account (free)

### Installation:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Pri23p/Health_App.git
   cd Health_App
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env.local` file in the root directory with:
   ```env
   NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
   PROJECT_ID=your_appwrite_project_id
   API_KEY=your_appwrite_api_key
   DATABASE_ID=your_database_id
   PATIENT_COLLECTION_ID=your_patient_collection
   APPOINTMENT_COLLECTION_ID=your_appointment_collection
   NEXT_PUBLIC_BUCKET_ID=your_bucket_id
   NEXT_PUBLIC_ADMIN_PASSKEY=111111
   ```

4. **Run the development server:**
   ```bash
   npm run dev
   ```

5. **Open your browser:**
   Visit `http://localhost:3000` to see the application

## 📱 How to Use

### As a Patient:
1. Open the application
2. Fill out the registration form with your details
3. Book an appointment with available doctors
4. Receive SMS confirmation for your appointment

### As an Admin:
1. Click the "Admin" link in the footer
2. Enter the passcode: `111111`
3. Access the admin dashboard
4. View and manage all appointments

## 🎓 Why This is Great for College Students

This project teaches you:
- Modern React development with Next.js 14
- TypeScript for type safety
- Backend integration with Appwrite
- Database management and CRUD operations
- Form validation with Zod
- Responsive design with TailwindCSS
- Real-world features like SMS notifications

## 📁 Project Structure

```
healthcare-main/
├── app/                 # Next.js app router pages
│   ├── admin/          # Admin dashboard
│   ├── patients/       # Patient routes
│   └── api/           # API routes
├── components/         # Reusable React components
│   ├── forms/         # Form components
│   ├── table/         # Data table components
│   └── ui/            # UI components
├── lib/               # Utility functions
│   ├── actions/       # Server actions
│   ├── validation.ts  # Form validation
│   └── utils.ts       # Helper functions
├── types/             # TypeScript definitions
├── constants/         # Constant values
└── public/           # Static assets
```

## 🔧 Setup Appwrite

1. Sign up for a free account at [appwrite.io](https://appwrite.io/)
2. Create a new project
3. Set up a database with two collections:
   - Patients collection
   - Appointments collection
4. Create a storage bucket for file uploads
5. Get your API keys and update the environment variables

## 📚 Learning Resources

- Next.js Documentation: https://nextjs.org/docs
- TypeScript Handbook: https://www.typescriptlang.org/docs/
- TailwindCSS Docs: https://tailwindcss.com/docs
- Appwrite Documentation: https://appwrite.io/docs








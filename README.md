# HealthCare Management System

A comprehensive healthcare patient management application that allows patients to easily register, book, and manage their appointments with doctors. The system includes advanced administrative tools for scheduling, confirming, and canceling appointments, along with SMS notifications. Built using **Next.js**, the project also features integration with **Appwrite**, **TailwindCSS**, **Twilio**, and more, ensuring responsiveness and smooth performance across all devices.

## 📋 Table of Contents
- 🤖 [Introduction](#introduction)
- ⚙️ [Tech Stack](#tech-stack)
- 🔋 [Features](#features)
- 🤸 [Quick Start](#quick-start)
- 🕸️ [Snippets](#snippets)
- 🔗 [Assets](#assets)
- 🚀 [More](#more)
- 🚨 [Tutorial](#tutorial)

## 🤖 Introduction
This healthcare management system allows patients to register and book appointments easily, while administrators manage appointment schedules and send SMS notifications for confirmations. Built with **Next.js**, the system ensures a seamless user experience and provides administrative control for efficient appointment handling.

For those new to web development, follow our in-depth video tutorial on [JavaScript Mastery YouTube](https://www.youtube.com/JavaScriptMastery). You can also join our active [Discord community](https://discord.gg/jsm) for additional support.

## ⚙️ Tech Stack
- **Next.js**: React framework for production-ready web apps.
- **Appwrite**: Backend as a service for managing authentication and databases.
- **TypeScript**: Strongly typed JavaScript for better development experience.
- **TailwindCSS**: Utility-first CSS framework for rapid UI development.
- **ShadCN**: UI components for modern web apps.
- **Twilio**: Cloud communications platform for sending SMS notifications.

## 🔋 Features
- **Register as a Patient**: Users can create personal profiles and register.
- **Book Appointments**: Patients can book multiple appointments with doctors.
- **Admin Management**: Administrators can view, confirm, schedule, and cancel appointments.
- **SMS Notifications**: Twilio integration sends SMS confirmation for appointments.
- **File Upload**: Appwrite storage allows secure file uploads.
- **Sentry Integration**: Monitor performance and detect errors with Sentry.
- **Responsive Design**: Full compatibility across all device types.

## 🤸 Quick Start
### Prerequisites
Make sure you have the following installed:
- **Git**
- **Node.js**
- **npm** (Node Package Manager)

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/adrianhajdin/healthcare.git
   cd healthcare
   ```

2. Install the project dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a `.env.local` file in the root directory and add the following:
   ```bash
   # APPWRITE
   NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
   PROJECT_ID=
   API_KEY=
   DATABASE_ID=
   PATIENT_COLLECTION_ID=
   APPOINTMENT_COLLECTION_ID=
   NEXT_PUBLIC_BUCKET_ID=

   NEXT_PUBLIC_ADMIN_PASSKEY=111111
   ```

   Replace placeholder values with your actual Appwrite credentials.

4. Run the project:
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) to view the app in the browser.

## 🕸️ Snippets
The following files are part of the code structure:
- `tailwind.config.ts`
- `app/globals.css`
- `types/index.d.ts`
- `types/appwrite.types.ts`
- `lib/utils.ts`
- `lib/validation.ts`
- `constants/index.ts`

## 🔗 Assets
More assets and instructions can be found in the repository.

## 🚀 More
For a detailed step-by-step guide, check out the full [tutorial on YouTube](https://www.youtube.com/JavaScriptMastery).

## 🚨 Tutorial
This repository is a part of a comprehensive tutorial available on the [JavaScript Mastery YouTube channel](https://www.youtube.com/JavaScriptMastery).


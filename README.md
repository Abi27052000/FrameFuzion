<div align="center">

  <div>
    <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-Cloudinary_AI-black?style=for-the-badge&logoColor=white&logo=cloudinary&color=F4F4F4" alt="cloudinary-ai" />
    <img src="https://img.shields.io/badge/-Clerk-black?style=for-the-badge&logoColor=white&logo=clerk&color=000000" alt="clerk" />
  </div>

  <h3 align="center">AI-Powered Social Media Image & Video Editing SaaS</h3>

</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)

## <a name="introduction">🤖 Introduction</a>

An AI-powered SaaS platform that allows users to upload images and videos for editing and compression. The application utilizes Cloudinary AI to automatically edit images based on context for various social media formats like Twitter Post, Facebook Cover, Instagram Portrait, and more. It also supports video uploads where the videos can be compressed and previewed. Built with Next.js and secured with Clerk for authentication.

## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- Clerk for Authentication
- Cloudinary AI
- TypeScript
- TailwindCSS

## <a name="features">🔋 Features</a>

👉 **Image Editing for Social Media**: Users can upload images and get them edited based on the context, tailored for platforms like Twitter, Facebook, Instagram, etc.

👉 **Video Upload and Compression**: Users can upload videos, and the app will automatically compress them for easy sharing.

👉 **Video Preview**: After compression, users can preview their video before downloading.

👉 **Cloudinary AI Integration**: Leverages Cloudinary AI to automatically adjust image formats and edit them according to the social media platform’s requirements.

👉 **Clerk Authentication**: Secure authentication and user management with Clerk.

👉 **Responsive Design**: The platform is fully responsive, providing a seamless experience on all devices.

👉 **User-Friendly UI**: Clean and modern interface built with TailwindCSS for easy navigation.

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/Abi27052000/FrameFuzion.git
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
#CLERK
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=

#CLOUDINARY
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
```

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

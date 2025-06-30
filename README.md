# StoreIt

StoreIt is a full-stack web application for managing online storage, similar to Google Drive or OneDrive. Built with modern technologies like Next.js, Appwrite, TypeScript, and shadcn/ui, it provides a seamless and secure experience for storing, sharing, and managing your files online.

![StoreIt Screenshot](./screenshots/screenshot.png)

[Live Project](https://store-it-beta-pied.vercel.app)

---

## Features

- **User Authentication:** Sign up, log in, and log out securely.
- **File Management:** Upload, update, and delete files with ease.
- **File Sharing:** Share files with other users via email or link.
- **User Dashboard:** View and manage your files in a clean, responsive interface.
- **Real-time Updates:** See changes reflected instantly.
- **Secure Storage:** All files and user data are securely managed via Appwrite.

---

## Technologies Used

- **Next.js:** React-based framework for server-side rendering and routing.
- **TypeScript:** Strongly-typed language for safer and more maintainable code.
- **Appwrite:** Backend-as-a-Service for authentication, database, and file storage.
- **shadcn/ui:** Beautiful, accessible UI components for a modern look and feel.
- **Tailwind CSS:** Utility-first CSS framework for rapid UI development.
- **Radix UI:** Accessible, unstyled UI primitives for building custom components.
- **React Hook Form & Zod:** For robust form handling and validation.


---

## Tech Stack

- **Frontend:** Next.js, React, TypeScript, Tailwind CSS, shadcn/ui, Radix UI
- **Backend:** Appwrite (cloud instance)
- **State Management:** Appwrite SDK, React hooks
- **Validation:** Zod, React Hook Form

---

## Running Locally

1. **Clone the repository:**
    ```bash
    git clone https://github.com/amanhaidry/StoreIt.git
    cd storeit
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Set up environment variables:**

    Create a `.env.local` file in the root directory and add the following (replace with your own Appwrite credentials if needed):

    ```env
    NEXT_PUBLIC_APPWRITE_ENDPOINT="https://nyc.cloud.appwrite.io/v1"
    NEXT_PUBLIC_APPWRITE_PROJECT="your_project_id"
    NEXT_PUBLIC_APPWRITE_DATABASE="your_database_id"
    NEXT_PUBLIC_APPWRITE_USERS_COLLECTION="your_users_collection_id"
    NEXT_PUBLIC_APPWRITE_FILES_COLLECTION="your_files_collection_id"
    NEXT_PUBLIC_APPWRITE_BUCKET="your_bucket_id"
    NEXT_APPWRITE_KEY="your_appwrite_key"
    ```

4. **Start the development server:**
    ```bash
    npm run dev
    ```

5. **Open [http://localhost:3000](http://localhost:3000) in your browser.**

---


**Happy Coding!**
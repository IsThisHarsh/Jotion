# Jotion

**Jotion** is a Next.js-powered web application inspired by Notion, providing a sleek and responsive interface for note-taking, document organization, and collaboration. It combines the flexibility of a Notion-like layout with modern web technologies to offer a seamless user experience.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Rich Text Editing**: Create and format notes with an intuitive editor.
- **Drag-and-Drop Layouts**: Organize content easily with flexible block structures.
- **Real-time Updates**: Synchronize changes instantly across multiple devices.
- **Multi-Page Structure**: Support for hierarchical organization of notes and documents.
- **Authentication**: Secure login and session management.
- **Cloud Deployment**: Easily deployable on Vercel for scalability.

## Technologies Used

- **Frontend**: Next.js, React, TypeScript
- **Styling**: Tailwind CSS for a clean and responsive UI
- **Database**: Firebase Firestore for cloud data storage
- **Authentication**: Firebase Auth for user management
- **State Management**: React Context API

## Prerequisites

Ensure you have the following installed before proceeding:

- [Node.js](https://nodejs.org/) (v16+ recommended)
- [npm](https://www.npmjs.com/)
- A Firebase project with Firestore enabled

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/IsThisHarsh/Jotion.git
   cd Jotion
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Configure environment variables**:

   - Rename `.env.example` to `.env.local`
   - Add your Firebase project credentials (API key, auth domain, project ID, etc.)

4. **Run the development server**:

   ```bash
   npm run dev
   ```

## Usage

1. **Open the application**:  
   Navigate to `http://localhost:3000` in your browser.

2. **Login** using Firebase authentication.

3. **Create and manage notes** using the editor interface.

## Screenshots

![Dashboard](screenshots/dashboard.png)  
*Example dashboard showcasing document organization.*

![Note Editing](screenshots/note_editing.png)  
*Rich text editing features in action.*

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a feature branch (`feature/my-feature`).
3. Commit your changes and push to GitHub.
4. Submit a pull request for review.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

For further details, visit the repository: [Jotion GitHub Repo](https://github.com/IsThisHarsh/Jotion).

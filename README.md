# Sorcery Gathering #10: Data Sorcerers Indonesia

## Overview

This repository contains the front-end web application for **Sorcery Gathering #10**, an event organized by Data Sorcerers Indonesia. The application provides a comprehensive platform for event participants, offering features such as registration, a personalized dashboard, certificate generation, and live event access.

## Features

*   **Home Page**: Engaging landing page providing information about Sorcery Gathering #10.
*   **User Registration**: Allows new participants to register for the event.
*   **User Login**: Secure authentication for registered users.
*   **Dashboard**: Personalized area for participants to view event details, schedules, and relevant information.
*   **Certificate Generation**: Enables participants to generate and download their event certificates.
*   **Live Event Access**: Provides a portal for accessing live event streams or content.
*   **Admin Panel**: (Implied from file structure) A dedicated section for administrators to manage event aspects.
*   **Feedback Mechanism**: (Implied from file structure) A system for participants to provide feedback.
*   **QR Scanner**: (Implied from file structure) A component for scanning QR codes, potentially for attendance or information retrieval.

## Project Structure

The project is structured to ensure modularity and maintainability. Key directories and their contents include:

```
. 
├── assets/                 # Contains static assets like images and icons
│   ├── icons/
│   └── images/
├── components/             # Reusable UI components (e.g., navbar, footer, modal)
│   ├── footer/
│   ├── modal/
│   ├── navbar/
│   ├── polling-widget/
│   └── qr-scanner/
├── gas/                    # Google Apps Script related files
├── pages/                  # Individual pages of the application
│   ├── admin/
│   ├── certificate/
│   ├── dashboard/
│   ├── feedback/
│   ├── home/
│   ├── live/
│   ├── login/
│   ├── register/
│   └── verify/
├── scripts/                # JavaScript files for application logic and routing
│   ├── api.js
│   ├── app.js
│   └── auth.js
├── styles/                 # Global and component-specific CSS styles
│   ├── global.css
│   └── variables.css
├── index.html              # Main entry point of the application
└── vercel.json             # Configuration file for Vercel deployment
```

## Technologies Used

*   **HTML5**: For structuring the web content.
*   **CSS3**: For styling the application, including `global.css` and `variables.css`.
*   **JavaScript**: For interactive functionality and application logic, including routing via `app.js`.
*   **External Libraries**: `heic2any.min.js`, `qrcode.min.js`, `html2canvas.min.js`, `jspdf.umd.min.js` for specific functionalities like image conversion, QR code generation, and PDF export.

## Setup and Installation

To set up the project locally, follow these steps:

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/chenko-the-sorcerers/sorcery-gathering.git
    cd sorcery-gathering
    ```

2.  **Navigate to the project directory**:
    The main application files are located in the `sorcery-gathering 2` subdirectory. You may need to adjust your path accordingly.
    ```bash
    cd "sorcery-gathering 2"
    ```

3.  **Open `index.html`**: 
    Since this is a front-end only application, you can open the `index.html` file directly in your web browser to view the application. For local development with a server, you can use a simple HTTP server (e.g., `python3 -m http.server`).

## Usage

Upon opening `index.html`, users can navigate through the various pages. The `app.js` script handles client-side routing, loading different page components and scripts dynamically. Registered users can log in to access their personalized dashboard and other features.

## Contributing

Contributions are welcome! Please feel free to fork the repository, make your changes, and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the LICENSE file for details (if available).

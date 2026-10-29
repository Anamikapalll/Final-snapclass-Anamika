SnapClass — AI-Powered Attendance System

SnapClass is a Python-based attendance management application built with Streamlit. It is designed to support attendance workflows using face and voice recognition.

Features

- Face Recognition: Supports face-based identification for attendance workflows.
- Voice Recognition: Includes voice-processing functionality.
- Attendance Management: Supports attendance-related operations.
- Database Integration: Uses Supabase for database connectivity.
- Interactive Interface: Provides a web-based interface using Streamlit.

Tech Stack

- Language: Python
- Frontend / UI: Streamlit
- Database: Supabase
- AI / ML: Face and voice processing libraries

Project Structure

snapclass/
├── app.py
├── src/
│   ├── components/
│   ├── database/
│   │   └── db.py
│   ├── pipelines/
│   │   ├── face_pipeline.py
│   │   └── voice_pipeline.py
│   └── screens/
├── requirements.txt
└── README.md

Note: This is an overview of the main files. Your actual folder structure may contain additional files.

Getting Started

Prerequisites

- Python compatible with the project's dependencies
- Git
- A Supabase project, if required by your configuration

Installation

1. Clone this repository:
   
   git clone YOUR_GITHUB_REPOSITORY_URL

2. Open the project directory:
   
   cd snapclass

3. Create a virtual environment:
   
   python -m venv venv

4. Activate it on Windows PowerShell:
   
   .\venv\Scripts\Activate.ps1

5. Install the dependencies:
   
   python -m pip install -r requirements.txt

6. Configure the required Supabase credentials using the project's secure configuration method.

7. Run the application:
   
   python -m streamlit run app.py

Configuration and Security

- Never commit API keys, passwords, database credentials, or private tokens.
- Keep local configuration files containing secrets out of version control.
- Configure your own credentials before running the application.

Future Improvements

- Improve the user interface and accessibility.
- Expand automated testing.
- Improve error handling and documentation.

Author

Developed by Anamika Pal.

Project Status

The application runs in the developer's local environment. Setup and feature availability may vary depending on system configuration and dependencies.
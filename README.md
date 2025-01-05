# Job Application Generator

This project is a Python-based tool for generating tailored job applications. It combines web scraping, AI-generated content, and a graphical user interface to help users create high-quality job applications quickly and efficiently. It automates the draft making process, allowing the user to generate several drafts tailored to different jobs. Original idea and a few lines of code written by mblystad,it was completed with a great deal of help from chatgtp/copilot. 

---

## Features

- **CustomTkinter GUI**: A user-friendly interface for input and interaction.
- **Web Scraping**: Extracts job descriptions and details from job postings (e.g., Finn.no).
- **AI-Powered Content Generation**: Uses Google Gemini AI to generate personalized job applications based on job descriptions and user-provided CVs.
- **File Support**: Reads CVs in `.pdf`, `.docx`, and `.txt` formats.
- **Image Upload**: Adds profile pictures to job applications.
- **Output Format**: Generates Word documents (`.docx`) with structured content.

---

## Requirements

- Python 3.8+
- The following Python libraries:
  - `customtkinter`
  - `Pillow`
  - `requests`
  - `beautifulsoup4`
  - `python-docx`
  - `pypdf`
  - `google-generativeai`

Install dependencies using:
```bash
pip install customtkinter pillow requests beautifulsoup4 python-docx pypdf google-generativeai
```

## How to Use
Set Up Google Generative AI API:

Add your Google Generative AI API key to the API_KEY variable in the script. This must be setup in your own Google AI studio account, it is free as of 05.01.2025 (subject to change).

**Follow the GUI Steps:**

Enter the job posting URL.
Select your CV file.
Optionally upload an image for the application.
Fill in your personal details.
Choose a tone for the application (Standard, Formal, Informal).
Click "Generer søknad" to create and save your application.

**Example Workflow**
Enter the URL of a job posting from Finn.no.
Select your CV file in .pdf, .docx, or .txt format.
Upload a profile picture (optional).
Provide your name, address, phone number, and email.
Select a tone (e.g., Formal) for the application.
Generate and save the application as a Word document.
Screenshots

**Known Issues**
Ensure the job posting URL is valid and accessible.
AI-generated content depends on the quality of the job description and CV.

**Future Enhancements**
Support for additional job posting platforms.
Enhanced customization of AI-generated text.
Multi-language support.

**License**
This project is licensed under the MIT License.

**Acknowledgments**
Google Gemini AI
Finn.no
Open-source libraries and contributors.

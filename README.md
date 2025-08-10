# Internship-Works


📄 README.txt  
==============

Project Title:
--------------
Real-Time Court Case Lookup using Manual CAPTCHA and Mock Data Fallback

Objective:
----------
This project aims to fetch and display real-time court case details from the official Indian eCourts website using Selenium automation with Flask as the web framework. Due to restrictions in CAPTCHA accessibility, a custom CAPTCHA system is implemented for manual validation, and mock data is used in case of real-time failure.

Technology Stack:
------------------
- Python 3.x  
- Flask  
- Selenium  
- HTML/CSS  
- Pillow (for CAPTCHA generation)  
- Chrome WebDriver  

Features Implemented:
----------------------
✅ Web-based input form for:
   - State  
   - District  
   - Court Complex  
   - Case Type  
   - Case Number  
   - Case Year  
   - CAPTCHA (custom generated)

✅ Custom CAPTCHA generation using Python  
✅ Form submission using Flask routing  
✅ Selenium-based automation to:
   - Open the official court site  
   - Auto-fill details  
   - Submit form  
   - Scrape and display case information

✅ Mock data fallback for:
   - Simulating output when real-time scraping fails (e.g., timeout, CAPTCHA errors, or site blocking)

✅ Result page to show case details or appropriate error messages  

Folder Structure:
------------------
project_folder/
│
├── app.py → Flask backend with CAPTCHA and form handling
├── court_scraper.py → Web scraping logic using Selenium
├── captcha_generator.py → Custom CAPTCHA generator
├── templates/
│ ├── index.html → Input form page
│ └── result.html → Case result display page
│
├── static/
│ ├── captcha.png → CAPTCHA image file
│ └── style.css → Styling for the HTML pages
│
└── README.txt → This file

Challenges Faced:
-------------------
❌ Real-time CAPTCHA from the court website cannot be fetched programmatically due to security restrictions  
✅ Implemented custom CAPTCHA for manual input and validation  
❌ Occasionally, the court website may load slowly or timeout  
✅ Integrated a mock response to ensure the application still provides output for demonstration  

How to Run:
------------
1. Ensure you have Python 3 installed  
2. Install dependencies:  
3. Download Chrome WebDriver and place it in your system path  
4. Run the application:  
5. Open your browser at `http://127.0.0.1:5000`  
6. Fill out the form with court details and enter the CAPTCHA shown  
7. Click **Fetch Case Details** to see real or mock data

**Declaration:**

I hereby declare that this project was developed by me for internship/academic purposes.  
No security mechanisms were bypassed in accessing court data.  
Mock data has been used only as a fallback for demonstration.  
This project is intended strictly for educational purposes.

**Submitted by:**

Name          : KAVYASRI  
Institution   : RAJALAKSHMI INSTITUTE OF TECHNOLOGY 
Project Title : Real-Time Court Case Lookup  
 






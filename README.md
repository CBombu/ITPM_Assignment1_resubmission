# ITPM_Assignment1_resubmission# IT23445154 – IT3040 Assignment 1 

##  Project Title
Automated Testing for Singlish to Sinhala Transliteration System

##  Repository

https://github.com/CBombu/ITPM_Assignment1_resubmission.git
---

##  Project Structure

IT3040_Assignment_1/

- test_automation.py           → Playwright automation script  
- IT23445154.xlsx → Excel file with test cases & results   
- IT23445154_requirements.txt             → Python dependencies   
- README.md                    → Project documentation  
- venv/ (optional)             → Virtual environment (not required)

---

##  Technologies Used

- Python  
- Playwright (UI Automation)  
- OpenPyXL (Excel handling)

---

##  How to Run the Project

1. Open terminal inside project folder  

2. (Optional) Activate virtual environment  
   venv\Scripts\activate  

3. Install dependencies  
   pip install -r requirements.txt  
   playwright install  

4. Run the automation script  
   python IT23445154.py --excel "IT23445154/IT23445154.xlsx" --url "https://www.pixelssuite.com/chat-translator" --input-col "Input" --expected-col "Expected Output" --actual-col "Actual Output" --status-col "Status" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

---

##  Output

- Results are automatically written to the Excel file  
- Columns updated:
  - Actual output  
  - Status (PASS / FAIL)  

---

##  Test Case Details

- Total Test Cases: 50+  
- Test Type: Negative Testing  

### Covered Scenarios:
- Mixed language inputs (Singlish + English)  
- Spelling variations  
- Emojis & symbols  
- Real-world scenarios (banking, travel, apps)  
- System-related messages (errors, logs)  
- Numeric and date inputs  

---

##  Important Notes

- This system uses strict comparison  
- Even small differences in Sinhala output (spacing, formatting, spelling) will result in FAIL  
- Some failures are expected due to:
  - Transliteration inconsistencies  
  - Mixed language complexity  
  - UI timing delays  

---

##  Student Information

- Student ID: IT23445154 
- Module: IT3040  
- Assignment: Assignment 1 (Option 1)  

---

##  Final Status

✔ Automation script working  
✔ Excel-based validation completed  
✔ Test coverage includes multiple edge cases  

---

##  Submission Notes

- Virtual environment (venv) is excluded from submission  
- All required files are included  
- Project is fully runnable using IT23445154_requirements.txt   

---

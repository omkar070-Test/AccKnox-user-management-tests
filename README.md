# AccKnox-user-management-tests  
## OrangeHRM User Management Automation

Automated end-to-end test suite using **[Playwright Python](https://playwright.dev/python/)** for the User Management module in [OrangeHRM](https://opensource-demo.orangehrmlive.com/).

---

##  Features Covered
- Navigate to Admin Module  
- Add a New User  
- Search the User  
- Edit User Details  
- Validate Updates  
- Delete the User  
- Confirm Deletion  

---

##  Project Setup

### 1. Create & activate virtual environment (recommended)
```bash
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Install Playwright browsers
```bash
playwright install
```

---

##  How to Run the Tests
```bash
pytest tests/test_user_management.py
```

---

##  Playwright Version
```
playwright==1.44.0
```

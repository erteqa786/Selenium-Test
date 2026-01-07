Used url: https://opensource-demo.orangehrmlive.com/web/index.php/auth/login 
AI Assistance url: https://chatgpt.com/share/695e14da-d830-8010-a10f-ee54067ab6db

📋 OrangeHRM Login Test Cases (Tabular Format)

----------------------------------------------------AI Generated Test Cases----------------------------------------------------------------
| TC ID | Test Scenario | Test Steps | Test Data | Expected Result |
|------|--------------|-----------|-----------|----------------|
| TC_01 | Valid Login | Open login page → Enter valid username → Enter valid password → Click Login | Admin / admin123 | Redirected to Dashboard |
| TC_02 | Invalid Password Login | Open login page → Enter valid username → Enter invalid password → Click Login | Admin / wrongpassword | "Invalid credentials" shown |
| TC_03 | Invalid Username Login | Open login page → Enter invalid username → Enter valid password → Click Login | Admin123 / admin123 | "Invalid credentials" shown |
| TC_04 | Empty Fields Validation | Open login page → Leave fields empty → Click Login | Blank / Blank | "Required" validation shown |
| TC_05 | Password Masking | Enter password in password field | admin123 | Password masked |

## 🧪 Test Scenario Covered
### ❌ Invalid Password Login Test
- Enter valid username and invalid password
- Verify error message: **"Invalid credentials"**
- Ensure user remains on login page

---

## 🛠️ Tech Stack
- Java
- Selenium WebDriver
- Maven
- ChromeDriver
- TestNG

## ⏳ Wait Strategy Used
- `Thread.sleep()` used before but with ai assistance 
- `WebDriverWait` used for dynamic error message

## Steps for the execution of the project:
1. Add TestNg, selenium-java depedencies in the pom.xml file
2. Ased AI to generate 5 test cases based on Login Functionality
3. Write the automated test script for testing the invalid password test case in the Test folder
4. Used AI assistance to dynamically enhance to project by using WebDriverWait instead Thread.sleep()
5. Used AI assistance to upload the project on github and Readme for the same

## Automated Test Script
<img width="1366" height="768" alt="Screenshot (188)" src="https://github.com/user-attachments/assets/784426a1-bafd-4421-a925-b0c1e8df7ce9" />

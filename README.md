# Selenium Login Automation

A Selenium WebDriver automation project built using Python that automates the login functionality of the SauceDemo website.

## Project Description

This project demonstrates how to automate a login process using Selenium WebDriver. The script opens the SauceDemo website, enters valid credentials, clicks the login button, and verifies whether the login was successful.

## Technologies Used

- Python
- Selenium WebDriver
- Chrome Browser
- VS Code
- Git & GitHub

## Website Tested

https://www.saucedemo.com/

## Test Scenario

1. Open the SauceDemo website.
2. Maximize the browser window.
3. Enter username: `standard_user`
4. Enter password: `secret_sauce`
5. Click the Login button.
6. Verify successful login by checking the URL.
7. Display login status in the console.

## Project Structure

```
selenium-login-automation/
│
├── login_test.py
├── requirements.txt
├── README.md
└── .gitignore
```

## Installation

### Clone the Repository

```bash
git clone https://github.com/vaibhavpatil452/selenium-login-automation.git
cd selenium-login-automation
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## Run the Script

```bash
python login_test.py
```

## Expected Output

```
Login Successful
```

## Sample Code

```python
driver.find_element(By.ID, "user-name").send_keys("standard_user")
driver.find_element(By.ID, "password").send_keys("secret_sauce")
driver.find_element(By.ID, "login-button").click()
```

## Future Enhancements

- Invalid login test cases
- Data-driven testing
- PyTest integration
- HTML reports generation
- Cross-browser testing

## Author

**Vaibhav Patil**

GitHub: https://github.com/vaibhavpatil452

## License

This project is created for learning and internship purposes.

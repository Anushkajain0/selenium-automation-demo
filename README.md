# Selenium Automation Demo

Maven-based Selenium + TestNG demo automating login on https://www.saucedemo.com.

## Contents
- `pom.xml` – Maven dependencies (Selenium, TestNG)
- `testng.xml` – TestNG suite
- `src/test/java/com/demo/LoginTest.java` – Example test
- `images/` – optional screenshots

## Tech stack
Java 17 | Maven 3.9 | Selenium 4.21 | TestNG 7.10

## Run on macOS
1. Make ChromeDriver executable:
   ```bash
   chmod +x /Users/anushkajain/Downloads/chromedriver-mac-arm64/chromedriver
   ```
2. Edit `LoginTest.java`:
   ```java
   System.setProperty("webdriver.chrome.driver",
       "/Users/anushkajain/Downloads/chromedriver-mac-arm64/chromedriver");
   ```
3. In terminal:
   ```bash
   mvn clean test
   ```
Reports appear in `target/surefire-reports/`.

## Notes
Heavy report folders were removed; run tests locally to regenerate them.

## Contact
GitHub: https://github.com/Anushkajain0/selenium-automation-demo
git add README.md
git commit -m "Add updated professional README"
git push


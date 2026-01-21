### **UI Test Checklist — Login Page**

**Project:** Sample Web Application

**Test type:** Manual UI Testing

**Page:** Login Page

**Environment:** Web (Chrome, Firefox), Windows 10



|ID|Test Scenario|Test Step / Check|Expected Result|Actual Result|Status|Comments|
|-|-|-|-|-|-|-|
|UI-01|Page Load|Login page loads correctly|Page loads within 3 seconds without UI breaks|As expected|Pass|—|
|UI-02|Page Layout|All elements are visible|Username, Password fields and Login button are displayed|As expected|Pass|—|
|UI-03|Logo|Company logo is displayed correctly|Logo is visible and not distorted|As expected|Pass|—|
|UI-04|Input Field|Username field accepts input|User can enter text into username field|As expected|Pass|—|
|UI-05|Input Field|Password field masks input|Password characters are hidden|As expected|Pass|—|
|UI-06|Button|Login button is clickable|Button is enabled and clickable|As expected|Pass|—|
|UI-07|Validation|Empty fields validation|Error message is shown for empty fields|Error displayed|Pass|—|
|UI-08|Validation|Invalid credentials|Error message "Invalid username or password" is shown|Error displayed|Pass|—|
|UI-09|UI Consistency|Alignment and spacing|Elements are aligned and evenly spaced|Minor misalignment|Fail|BUG-101|
|UI-10|Responsiveness|Mobile view layout|Page adapts correctly to mobile resolution|As expected|Pass|Tested on Chrome DevTools|




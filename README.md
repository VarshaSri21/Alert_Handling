# Alert_Handling

<p align="justify">This repository contains a case study and automation script for handling alerts on a web page using Selenium WebDriver. The case study focuses on two scenarios: handling an alert when the user clicks on the "Sign in" button without filling any information and handling an alert when the user clicks on the "Forgot Password" link without filling any details.</p>

__Problem Statement__

The problem statement revolves around handling alerts in specific scenarios on the web page. The two scenarios to be addressed are as follows:

1. **Handling the "Sign in" button alert**: The alert should be handled when the user clicks on the "Sign in" button without filling any information.
2. **Handling the "Forgot Password" link alert**: The alert should be handled when the user clicks on the "Forgot Password" link without filling any details.

__Suggested site__: : [rediff.com](https://mail.rediff.com/cgi-bin/login.cgi).

__Detailed Description__:

- Launch the browser 
- Enter URL: : [https://mail.rediff.com/cgi-bin/login.cgi](https://mail.rediff.com/cgi-bin/login.cgi).
- Keep all the fields empty 
- Click on Sign In button 
- Fetch the text of Alert 
- Close the alert 
- Verify whether correct alert is displayed against expected text of Alert. 
- Click on Forgot password link 
- Click on Next button without filling details 
- Fetch the text of Alert 
- Close the alert 
- Verify whether correct alert is displayed against expected text of Alert. 
- Close the browser 

__Key Automation Scope__: 

- Automation Concepts, Selenium Configuration, Web driver Basics 
- Object Identification By name 
- All Web elements(locators) 
- Page Navigation 
- Relative XPath 
- Form Registration Basic 
- Form Registration Advanced 
- Reusable method creation 
- Alert Handling 
- Driver setup and browser capabilities 
- Test case validation

__Prerequisites__

To execute the provided automation script, you need to have the following:

- Java installed on your machine
- Selenium WebDriver library installed
- Web browser (e.g., Chrome, Firefox) with the respective driver executable.

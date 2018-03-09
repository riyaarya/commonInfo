# RedBus


1: Click on profile icon and do signup
---------------------------------------
2: After the successful signup find bus from Delhi to Dehradoon
------------------------
3: Select the date  using date time picker
-------------------
4: Select a bus 
-------------------
5: Click on view seats
-------------------
6: Select a seat
-------------------
7: check if the price is lower than 500 then click on  proceed
-------------------
8: Enter passenger details and male and female radio button
-------------------
9: Check the price of final amount on pay screen and click on pay of price is higher than 600 only
--------------------------------------

----------------------------------------------------------------------------------------------

# Usefull links

To use chrome
https://stackoverflow.com/questions/13724778/how-to-run-selenium-webdriver-test-cases-in-chrome

Radio button
http://toolsqa.com/selenium-webdriver/checkbox-radio-button-operations/

Datepicker
https://www.guru99.com/handling-date-time-picker-using-selenium.html

canvas
https://sqa.stackexchange.com/questions/3253/how-to-automate-the-action-on-a-canvas-object-when-the-canvas-element-has-no-na
https://chariotsolutions.com/blog/post/automated-testing-of-html5-canvas/

Browser notifocation
http://www.globalsqa.com/handle-browser-notification-selenium/



WebDriver driver ;
        FirefoxProfile profile = new FirefoxProfile();
        profile.setPreference("permissions.default.desktop-notification", 1);
        DesiredCapabilities capabilities=DesiredCapabilities.firefox();
        capabilities.setCapability(FirefoxDriver.PROFILE, profile);
        driver = new FirefoxDriver(capabilities);
        driver.get("your Web site"); 

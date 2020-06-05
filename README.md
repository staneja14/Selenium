# Selenium
This repository contains code examples for Selenium WebDriver in Java

Important Points:-

1. The first step is to create a Driver object for Chrome Driver. If you create an object for a class, driver is created 
automatically.

2. Once the driver is created we will implement its methods. Web Driver is nothing but an interface which provides all the
methods for automation. Driver is an interface.

3. We have to do one more thing to invoke the browser. The .exe file is the browser driver file. You have to mention the file 
path in System.setProperty() method.

4. Every object may not have an ID, className or name. So, CSS and XPath are preferred. 

5. The aplha numeric ID may vary on every refresh. So, check twice.

6. Always confirm the link object with anchor 'a' tag.

7. The classes should not have spaces. Compound classes should not be accepted.

8. If there are multiple values in a file, Selenium identifies the first. It scans thee file from top left.

9. Double quotes inside double quotes are not accepted. 

10. XPaath and CSS can be identified in 'n' number of ways.

11. To generate XPath, right click and copy the blue highlighted portion.

12. Whenever you see XPath starting with HTML, it's not reliable. Switch the browser to get another one.

13. There is no direct way to get CSS in chrome. You'll find it in the tool bar.

14. Whenever you have to verify in the console, use $x(" ") for XPath and $(" ") for CSS. 

15. The CSS Syntax is:-

    tagName[attribute = 'value'], tagName#id, tagName.className 
    
    XPath Syntax:-
    
    tagName[@attribute = 'value']
    
16. XPath Regular Expression syntax: 
    tagName[contains(@attribute, 'value')]. 
   'contains' here should contain the actual value. If you're passing the actual teext then give only attribute = 'value' but     if you're giving the subtext to match then write 'contains'.
   
17. CSS Regular Expression syntax: tagName[attribute* = 'value'].If you think that attributes are changing i.e. it's dynamic 
    then use this regular expression.
    
18. 
    
    


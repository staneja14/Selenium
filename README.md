# Selenium
This repository contains code examples for Selenium WebDriver in Java

**Important Points:-**

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

15. **The CSS Syntax is:-**

    tagName[attribute = 'value'], tagName#id, tagName.className 
    
    **XPath Syntax:-**
    
    tagName[@attribute = 'value']
    
16. **XPath Regular Expression syntax:**
    tagName[contains(@attribute, 'value')]. 
   'contains' here should contain the actual value. If you're passing the actual teext then give only attribute = 'value' but     if you're giving the subtext to match then write 'contains'.
   
17. **CSS Regular Expression syntax:** tagName[attribute* = 'value'].If you think that attributes are changing i.e. it's            dynamic then use this regular expression.
    
18. **Locators**: A locator is a query that results in 1-N eleements being returned to you, the majority of the time, it will 
      a single element.
      
      Selenium provides many methods to find elements:
      
      1. **ID**: This is thee preferred approach as ID tends to be unique, meaning that your locator will be reliable, even if            the site was re-designed or additional content was added. Easiest waay to find whether an element has ID or not is
           to use developer tools.
           
      2. **Name**: It's same as ID. Name isn't much used by developers. 
      
      3. **CSS Selector**: It allows us to send a query to Web Driver. So, instead oof saying find an element by ID, we can be 
         very specific, or instruct WeebDriver to follow a pattern. If I can't find an element directly with something unique,
         I'll always turn to a CSS selector. 
         
      4. **ClassName**: Classes are commonly not unique on a page. By.class will search all the eleements on a page aand                return you the first one that has the value provided in the class attribute. 
      
      5. **TagName**: It's rarely used. It will return the first element on the page. Eg.: div, p, form etc.
      
      6. **LinkText**: 
      
          Eg. <a href = "#"> here </a>
          driver.findElement(By.linkText("here"))
          
          It will return the first one that maatches the text, used mostly on navigation menus.
          
      7. **PartialLinkText**: It will check all your anchor tags on page and see if the teext of them partially mathces your 
           query.
      
      
    
    



### Practice Questions:-

1. Briefly describe the differences between the webbrowser, requests, bs4, and selenium modules.

**Answers**
```
webbrowser it launchs a web browser to a specific URL.

requests is used to download files and pages from the Web.

bs4 to parse HTML

selenium is used to control a webbrowser
```
2. What type of object is returned by requests.get()? How can you access the downloaded content as a string value?

**Answers**
```
Response object and using text attribute we has the downloaded content as a string value.
```
3. What requests method checks that the download worked?

**Answers**
```
raise_for_status() checks for  exceptions .
```
4. How can you get the HTTP status code of a requests response?

**Answers**
```
status_code attribute of the Response object contains HTTP status code.
```
5. How do you save a requests response to a file?

**Answers**
```
use 'wb' “write binary” mode and a for loop that iterates over the Response object’s iter_content() method.
```
6. What is the keyboard shortcut for opening a browser’s developer tools?

**Answers**

```
<kbd>⌘</kbd>-<kbd>OPTION</kbd>-<kbd>C</kbd>
```
7. How can you view (in the developer tools) the HTML of a specific element on a web page?

**Answers**
```
Inspect Element
```
8. What is the CSS selector string that would find the element with an id attribute of main?

**Answers**
```
'#main'
```
9. What is the CSS selector string that would find the elements with a CSS class of highlight?

**Answers**
```
'.highlight'
```
10. What is the CSS selector string that would find all the <div> elements inside another <div> element?

**Answers**
```
'div div'
```
11. What is the CSS selector string that would find the <button> element with a value attribute set to favorite?

**Answers**
```
'button[value="favorite"]'
```
12. Say you have a Beautiful Soup Tag object stored in the variable spam for the element <div>Hello, world!</div>. How could you get a string 'Hello, world!' from the Tag object?

**Answers**
```
spam.getText()
```

13. How would you store all the attributes of a Beautiful Soup Tag object in a variable named linkElem?

**Answers**
```
inkElem.attrs
```
14. Running import selenium doesn’t work. How do you properly import the selenium module?

**Answers**

```from selenium import webdriver```

15. What’s the difference between the find_element_* and find_elements_* methods?

**Answers**
```
return the first matching element and returns list of matching elements.
```
16. What methods do Selenium’s WebElement objects have for simulating mouse clicks and keyboard keys?

**Answers**

``` click() and send_keys()```

17. You could call send_keys(Keys.ENTER) on the Submit button’s WebElement object, but what is an easier way to submit a form with selenium?

**Answers**
```
Calling submit() is easier way.
```
18. How can you simulate clicking a browser’s Forward, Back, and Refresh buttons with selenium?

**Answers**

```forward(), back(), and refresh()```

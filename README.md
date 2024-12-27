In this project, we have created automated tests for some of the functionalities of the already developed and publicly available website https://www.nay.sk/.

## Tests Design

We have prepared the following test cases (TC):

- TC_01: Verify the availability of the website https://www.nay.sk/.
- TC_02: Verify the functionality of the product attributes filters.
- TC_03: Verify the ability to add a selected product to the shopping cart on the website.

Detailed information about the test cases are listed in the *csv file*.

## Description of Automated Testing

To create automated tests, we used Selenium IDE, installed as an extension for the Firefox web browser, to create the automated tests.
-	Tests created in Selenium IDE
    -	the tests use basic Selenium IDE commands
-	Actions used in Selenium IDE
    -	search and open page
    - search element by xpath
    - set window size
    - verify text, verify element
-	We located the webpage elements using XPath
    -	for verifying the created XPaths, we used xPath Helper
-	Tests export to Java
    -	the basic tests were exported to a Java file. The source code of the tests in Java can be found in the „tests_java“ folder

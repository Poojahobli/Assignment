# Assignment

Code will execute if we have selenium and Rest Assured libraries.

Logic is:
1)Firstly landed on page:https://developer.here.com/documentation
2)Divided links in to 2 sections
 ==>links which present in dropdown
 ==>links which is not in Dropdown
3)Took all links which is in Dropdown and traversed through each and every link using For loop and get a Response by using RestAssured 
4)Checked Response code,if it is not Equal to 200 then i will print URL with Response code.
5)Took Rest of the links and traversed through each and every link using For loop and get a Response by using RestAssured 
6)Checked Response code,if it is not Equal to 200 then i will print URL with Response code.

Result:
Test passed as it couldn't find any broken link.
 

# Mobile application testing
I tested a mobile application "shopping-list", designed for creating and managing a list of tasks.

## Requirements analysis and test documentation preparation:

[Check list](https://docs.google.com/spreadsheets/d/1ZDBFI9ZM9S9ehtDhM_fdagTEnRy36m8_UTYZ_KH_eWE/edit?usp=sharing)

[Test cases](https://github.com/KseniiaPetrova923/mobile/blob/main/test_cases.pdf)

## Functional testing:

[Bug report](https://github.com/KseniiaPetrova923/mobile/blob/main/Issues.xlsx)

[Test run results](https://github.com/KseniiaPetrova923/mobile/blob/main/test_run.pdf)

## Test summary report:
To analyze the quality of the shopping-list mobile application, I compiled a test summary report, including:
-the total number of launched test cases and their results.
-the number of defects found, classified by priority.
-analysis of test coverage of key functionality.
-conclusions about the current state of the product.
[Test summary report ](https://github.com/KseniiaPetrova923/mobile/blob/main/Test%20Summary%20Report.pdf)

## Using of Charles Proxy:
To test the shopping-list mobile application, I used a sniffer to intercept, modify and analyze HTTP requests. As part of testing, I completed the following tasks.

*Changing the request to remove an item from the cart:
Using a breakpoint, I intercepted a request to delete one product and changed it so that another product was deleted instead.

*Simulation of content substitution:
I set up interception of a request to https://demoshopping.ru and changed the response so that a random picture was loaded instead of the site.

*Intercepting an HTTPS request from a mobile device:
I analyzed the application’s network traffic and recorded one of the intercepted requests.


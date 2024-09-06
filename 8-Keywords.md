## Keywords

AssureQA is a keyword-driven framework, featuring unique keywords that replicate user interactions with the application under test, setting it apart from other automation tools.

| **Keyword**                   | **Description**                                                                 |
| ----------------------------- | ------------------------------------------------------------------------------- |
| **GOTOURL**                   | Navigate to the specified URL.                                                   |
| **VALIDATETITLE**             | Get the actual title of a web page and compare it with the expected title.       |
| **SETTEXTVALUE**              | Set values in an input text field. Accepts plaintext, variables, and functions.  |
| **CLICK**                     | Perform a mouse click operation on any interactive UI element (links, buttons, checkboxes, radio buttons). |
| **SCROLL**                    | Scroll to a designated element on the webpage.                                   |
| **WAITELEMENT**               | Wait for a particular element.                                                   |
| **SWITCH**                    | Switch control to the next tab or window.                                        |
| **CLEAR**                     | Clear the value of an input field.                                               |
| **SWITCHTOIFRAME**            | Switch control to the specified iframe.                                          |
| **DOWNLOAD**                  | Download a file.                                                                |
| **UPLOADFILE**                | Upload a file downloaded from a source.                                          |
| **SWITCHTOALERT**             | Switch to an alert dialog.                                                       |
| **EXIT**                      | Exit the browser.                                                               |
| **ISDISPLAYED**               | Check if a particular element is present on the webpage.                         |
| **SWITCHWINDOW**              | Switch from one window to another.                                               |
| **DISMISSALERT**              | Close the alert message.                                                        |
| **SELECTOPTION**              | Select an option from a dropdown list.                                           |
| **CUSTOMJS**                  | Execute JavaScript code.                                                         |
| **KEYSTROKE**                 | Perform specific keyboard functions.                                             |
| **VERIFYTEXT**                | Verify if a specific value is present on the screen.                             |
| **SWITCHTOPARENTFRAME**       | Switch from an iframe back to the parent frame.                                  |
| **CAPTURETEXT**               | Capture the text of an element.                                                  |
| **DRAGANDDROPWITHLOCATOR**    | Drag and drop using locator values.                                              |
| **INFO**                      | Display information.                                                            |
| **RIGHTCLICK**                | Right-click a particular element.                                                |
| **DRAGANDDROPWITHCOORDINATE** | Drag and drop using coordinate values.                                           |
| **FORLOOP**                   | Repeat a block of code for each item in a collection or a set number of times.   |


# FOR LOOP

A key feature provided by AssureQa is the "For Loop." As the name suggests, it allows users to iterate a set of test steps with multiple data inputs, thereby enhances the test coverage and reduce maintenance efforts.

To use the for loop in a testcase, there must be a [Creating Reusable Steps](), [Dataset]() and [Variables]() inputs. Test steps which’re expected to be iterated must be grouped to form a shared test. Then add variables to the required test steps and the same variables must be added to a dataset. Ok, then let’s see how these processes can be done step by step.

**Adding ‘For Loop’ to the testcase**

1. Go to testcase page, select the desired testcase.

![F1](/images/F1.png)

2. Click on the ‘+’ icon of the test step below which you want to add the ‘For Loop’.

![f2](/images/f2.png)

3. Click on action field, it will list all available keywords.
4. Select “For Loop”.

![f3](/images/f3.png)

5. Enter element name (optional).

![f4](/images/f4.png)

6. Click on dataset name field, select desired one.

![f5](/images/f5.jpg)

7. Select desired override value column index of the selected dataset at the ‘From’ field.
8. Select desired override value column index of the selected dataset at the ‘To’ field, but the value must be greater than that given in the ‘From’ field.

![F6](/images/f6.png)

9. Click on shared name field, select desired one.

![F7](/images/f7.png)

10. Click on “Add step”. The test step will be added successfully.

![F8](/images/F8.png)

The set of steps within the shared test that are added in the for loop will be repeated with different data in a single run.

**Executing a Testcase having For loop**

Just as we know how to execute a test case or test flow, we can execute a test case with the ‘for loop’ in the same ways. Click the run button after selecting the desired environment, browser, and its version, or use the default settings if preferred. Executing this testcase inside flow also will also be normal manner.
Refer [Running Test Case](), [Running a Flow]() .

**For Loop’s Report View-Unit report and Flow report**

After successful execution of the testcase, one can find the ‘for loop’ step in the unit/flow report as a single step with a drop-down arrow button on it.

**Inside unit report**

 1. Execute a testcase having for loop.
 
 ![f9](/images/f9.png)

 2. Go to unit report.
 3. Click on the test report which opens to a detailed summary report and there the “for loop” appears as a single step.
 4. Click on drop-down button, it will display all iterations

 ![f10](/images/f10.png)

 5. Verify the results by comparing the screenshots available in these test steps (if added).
 
 **Inside flow report**

 1. Execute test flow with a testcase having for loop in it.
 
 ![f11](/images/f11.png)

 2. Go to Flow report.
 
 ![f12](/images/f12.png)

 3. Click on the flow report which opens to a detailed report showing flow structure
 4. Click on suitenode which will open the suite report.
 5. Click on the testcase with for loop where it appears as a single step.
 7. Click on drop-down button of the for loop step to display all iterations.

 ![f13](/images/f13.png)

 8. Verify the results by comparing the screenshots available in these test steps (if added).

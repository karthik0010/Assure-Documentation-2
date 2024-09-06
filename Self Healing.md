
# Self Healing


AssureQA leverages AI to identify and resolve script failures caused by unexpected errors. It employs a method based on script healing and character recognition principles, while also offering traditional element identification through locators. By enabling the script healing method, AssureQA provides flexibility during script execution.

To demonstrate this, let's take a dynamic site in which the elements inside this site are keep changing. Assume that we need to make a click on a button called "Hotels" and it's locator, say id="hotel1" is changing after some time.

![Self Healing](images/scr2.jpg)

1. Copy the url of this site and paste it on the recorder page.
2. Start recording the events like click on the "Hotels" button.
3. Save the recordings and form a testcase
4. Goto the testcase page and select the created testcase

![Self Healing](images/scr3.png)

5. Open Config and Enable Self Healing Option marked in the picture.

![Self Healing](images/scr4.png)

6. The test case should be executed after saving.
At this time, the test case will be passed.

![Self Healing](images/scr5.png)

Assume that now that locator value has been changed , like changed to id="hotel2".

![Self Healing](images/scr6.png)

But without making any changes to the saved locators, we just rerun the testcase. Due to script healing feature, the step with changed locator will be executed successfully. 

![Self Healing](images/scr7.png)

If script healing had happened, then the element on which the action performed will be marked with a red rectangular box in the screenshot.

![Self Healing](images/scr8.png)

In this way, Assureqa's script healing perform the automatic maintenance and correction of test scripts that break due to changes in the application under test.

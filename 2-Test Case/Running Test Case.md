# Running the Testcase

Now let's see how the Testcase can be executed.

By clicking the Test config option the user would be able to select the required browser and environment if needed. Here we can change testcase name, description and Tags as per user wish.

![Test config(Running Testcase)](./TestcaseImages/1.Test%20config(Running%20Testcase).png)

Another option inside the config is advanced settings which includes adaptive wait, always take screenshot and screen resolution setup. When employing Adaptive wait, each step in the testcase waits for an element to the provided time frame.

Also, there's option for selecting screenshots. Enable the toggle button if you want to take screenshots in all steps, and disable it if screenshots are not needed in all steps. This is also dependent on the test steps screenshot condition.

**Test step settings**

Clicking on a test step reveals these options, which vary depending on the selected Action.

![TestSteps(Running Testcase)](./TestcaseImages/2.TestSteps(Running%20Testcase).png)

In this instance, "SETTEXT" has been chosen, offering options such as "Definition" allowing the user to input plain text and incorporate variables and built-in functions as needed.

![Input Values to definition(Running Testcase)](./TestcaseImages/3.Input%20Values%20to%20definiton(Running%20Testcase).png)

Following this, the element name is identified, and users can set it according to their preferences until it is utilized for the scripting healing.

Moving forward, there are locators that can be edited or added based on user requirements

**Advanced settings inside Test Step**

Here we can see 3 conditions

**1.**  **Mark error and stop**  
**2.**  **Mark error and continue**  
**3.**  **Mark warning and continue**

![4.Three conditions(Running Testcase)](./TestcaseImages/4.Three%20conditions(Running%20Testcase).png)

**Mark error and Stop**
This is the default condition for all test steps. If this condition is applied, when that specific step is executed, the run comes to a halt.

![5.Mark Error and Stop(Running Test Case)](./TestcaseImages/5.Mark%20Error%20and%20Stop(Running%20Test%20Case).png)

**Mark error and continue**

![Mark Error and Continue(Running TestCase)](./TestcaseImages/6.Mark%20Error%20and%20Continue(Running%20TestCase).png)

When this condition is chosen, the step will pass but it marks an error for that specific step.

**Mark warning and continue**

![Mark Warning and Continue(Running Test Case)](./TestcaseImages/7.Mark%20Warning%20and%20Continue(Running%20Test%20Case).png)

When this condition is used then that step displays a warning and continues the execution

**Report history**

Clicking on this icon allows the user to view all reports related to that particular test case.

![Reports of all test cases(Running Test case)](./TestcaseImages/8.Reports%20of%20all%20test%20cases(Running%20Test%20case).png)

**Passed testcase**

Since all steps have passed, it indicates successful execution.

![Passed TestCase(Running TestCase)](./TestcaseImages/9.Passed%20TestCase(Running%20TestCase).png)

**Failed testcase**

A step has failed here, leading to the termination of the execution at that particular step.

![Failed Test Case(Running Test Case)](./TestcaseImages/10.Failed%20Test%20Case(Running%20Test%20Case).png)

**Show failed step**

This feature enables the user to view all the failed steps.

![Show only failed(Running Test Case)](./TestcaseImages/11.Show%20only%20failed(Running%20Test%20Case).PNG)

**Live view**
Assureqa also allows user to view the live view of the test runs.For that, just click on the toggle button at the testcase editor and so the live view will be available at the view section at the testcase editor as well as inside the unit report.

-Inside test case editor

![LV](/images/tc_d.png)

-Inside test report

![LV](/images/tc_d.png)

**Edit Actions in Test Step**
We have several options available to modify steps, including Delete, Enable, Disable, Cut, Copy, and the ability to create a reusable step.Let's explore the procedures connected with these buttons.

**Delete step**

This feature enables the user to remove a step.

![Delete TestStep](./TestcaseImages/12.Delete%20Step(Running%20Test%20Case).png)

**Enable step**

This functionality permits the user to activate a disabled step.

![Enable TestStep(Running TestCase)](./TestcaseImages/13.Enable%20TestStep(Running%20TestCase).png)

**Disable step**

This functionality empowers the user to deactivate a step.

![Disable TestSep(Running Test Case)](./TestcaseImages/14.Disable%20TestSep(Running%20Test%20Case).png)

**Cutting a Test Step**

![Cutting TestStep(Running TestCase)](./TestcaseImages/15.Cutting%20TestStep(Running%20TestCase).png)

![Pasting TestStep(Running Test Case)](./TestcaseImages/16.Pasting%20TestStep(Running%20Test%20Case).png)

This feature enables the user to cut and paste a test step to an exact position. User can also click and drag test step to arrange steps.

**Copying a Test Step**

![Copy TestStep(Running Test Case)](./TestcaseImages/17.Copy%20TestStep(Running%20Test%20Case).png)

![Pasting Copied TestStep(Running Test Case)](./TestcaseImages/18.Pasting%20Copied%20TestStep(Running%20Test%20Case).png)

This functionality enables the user to copy and paste the test step to a precise position with a simple click on the destination.

**Reusable step icon**

![Create Reusable Test Step(Running Test Case)](./TestcaseImages/19.Create%20Reusable%20Test%20Step.png)

This icon allows user to create reusable steps.

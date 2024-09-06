
## Visual testing

Assureqa offers a Visual Testing feature. This ensures a consistent user experience by identifying design changes early .It involves capturing and comparing screenshots of the UI during testing to detect any unintended changes or visual discrepancies. Visual Testing is disabled by default for test steps, but you can enable it for specific steps requiring visual validation.

**Steps to configure visual testing for a test step within a test case**

1. Go to testcase page select the required testcase to perform
2. Click on test step, enable visual testing in the test step by clicking on the toggle button.
3. Click on save button

![vi1](/images/vi1.png)

> [!Note:]
> Once you enable visual testing, AssureQA requires a baseline image corresponding to the test step to perform visual testing. So, the visual comparison will appear on the test step only after a run.
> When performing visual testing with AssureQA, you need to compare the current image (actual image) with the original image (baseline image) to ensure they match.

**Running visual test on testcase**
1. After enabling the visual testing button, click on the run button
2. A baseline image has been created, run the test again to compare it with the original image.
3. In the second run, there appears an icon indicating the visual validation.

![vi2](/images/vi2.png)

4. Upon clicking the icon, a pop-up will be displayed.
The images contain visual differences, then report will show the comparison as "true." If there are no differences, it will display as "false."

![vi3](/images/vi3.png)

> [!Note:]
> You can also run it on the Test flow.

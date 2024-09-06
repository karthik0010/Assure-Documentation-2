# 👁️ Visual Testing in AssureQA

AssureQA offers a **Visual Testing** feature to ensure a consistent user experience by identifying design changes early. This feature captures and compares screenshots of the UI during testing to detect any unintended changes or visual discrepancies. By default, Visual Testing is disabled for test steps, but you can enable it for specific steps that require visual validation.

---

## 🔧 Configuring Visual Testing for a Test Step

To enable visual testing for a specific test step, follow these steps:

1. **Navigate to the Test Case Page**:
   - Select the required test case to configure visual testing.

2. **Enable Visual Testing**:
   - Click on the test step where visual validation is needed, and toggle the **Visual Testing** option.

3. **Save the Changes**:
   - Click on the **Save** button to confirm the settings.

   ![vi1](/images/vi1.png)

> [!NOTE]
> Once you enable visual testing, AssureQA requires a **baseline image** for the selected test step. The visual comparison will appear only after a test run. Visual testing compares the current image (actual) with the original image (baseline) to ensure they match.

---

## 🚀 Running Visual Tests on a Test Case

1. **Run the Test**:
   - After enabling visual testing, click the **Run** button to execute the test.

2. **Capture the Baseline Image**:
   - On the first run, a baseline image will be captured. Run the test again to compare it with the baseline image.

3. **Visual Validation**:
   - On the second run, an icon indicating visual validation will appear.

   ![vi2](/images/vi2.png)

4. **Review Visual Comparison**:
   - Click the visual validation icon to display a pop-up with the comparison between the actual image and the baseline image.
   - If the images contain visual differences, the report will show the comparison as "true." If there are no differences, it will display as "false."

   ![vi3](/images/vi3.png)

> [!NOTE]
> Visual Testing can also be executed in a **Test Flow**.

---


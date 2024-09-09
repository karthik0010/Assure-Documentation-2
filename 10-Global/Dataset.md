# 🌟 Mastering Datasets in AssureQA

Datasets in AssureQA organize and manage variables efficiently, allowing for easy data management and testing scenarios across multiple data sets. This guide walks you through creating and managing datasets dynamically.

## 🛠️ Creating and Managing Datasets

### Step-by-Step Creation

1. **Navigate to Dataset**:
   Access the Global menu and select the Datasets section to start creating a new dataset.

   ![Create Dataset](/DatasetImages/d1.png)

2. **Enter Dataset Details**:
   Click 'Create dataset', enter a name for your dataset, and finalize creation.

   ![Dataset Details](/DatasetImages/d2.png)

3. **Add Override Values**:
   Manually input override values or use built-in functions to tailor data for your test scenarios.

   ![Add Override](/DatasetImages/d4.png)

4. **Function Integration**:
   Enhance datasets by incorporating functions directly into your dataset fields for dynamic data manipulation.

   ![Function Integration](/DatasetImages/d6.png)

5. **Expand Dataset**:
   Add additional columns to accommodate more override values as your testing expands.

   ![Expand Dataset](/DatasetImages/d8.png)

## 📥 Importing and Exporting Data

1. **Export to CSV**:
   Download your dataset template or current data as a CSV file, modify it externally, and re-import for updated testing scenarios.

   ![Export CSV](/DatasetImages/d11.png)

2. **Import Updated Data**:
   Reintegrate your modified CSV files to update datasets with new or changed data seamlessly.

   ![Import CSV](/DatasetImages/d12.png)

---


---

**Adding Dataset to Test case**

We can use dataset in two ways inside a testcase. One way is applying it directly to the testcase and other way is applying it only to the shared steps i.e, via For Loop. First method's steps are mentioned below and for the other one, please refer 'for loop' section.

 1. Goto test case page.
 
 2. Select desired test case and that must contains variables same as that in the created dataset.
 
 3. Open testcase editor of selected test case. 
 
 4. Click on the dataset dropdown button on the top mid-right corner of testcase editor page.
 
 ![d17](/DatasetImages/d17.png)
 
 5. Select created dataset and the selected one's name will be shown on the field.

 ![d18](/DatasetImages/d18.png)
 
 ![d19](/DatasetImages/d19.png)

---

## 🔄 Using Datasets in Test Flows

Leverage datasets effectively within your test flows for enhanced testing precision:

1. **Link Dataset to Test Case**:
   In the test flow page, attach your dataset to a suite node or directly to individual test cases for dynamic data application.

   ![Link Dataset](/DatasetImages/d20.png)

2. **Select Dataset in Editor**:
   Choose the appropriate dataset from the dropdown in the suite node editor to apply it to your test cases.

   ![Select Dataset](/DatasetImages/d21.png)

---


## 🛠️ Dataset Maintenance

### Update or Delete Datasets

- **Update Dataset**:
  Make necessary changes to your dataset through the update option in the dataset tab.

  ![Update Dataset](/DatasetImages/d23.png)

- **Delete Dataset**:
  Remove unnecessary datasets to keep your data management streamlined.

  ![Delete Dataset](/DatasetImages/d25.png)

---

### Dynamic Filtering and Navigation

- **Dataset Filters**:
  Quickly find datasets by maintainer or name using dynamic filters that update your view instantly.

  ![Dataset Filters](/DatasetImages/d27.png)

- **Page Navigation**:
  Move between different dataset management screens easily, enhancing your workflow efficiency.

  ![Navigation](/DatasetImages/d28.png)

Harness these advanced features in AssureQA to create, manage, and utilize datasets effectively, ensuring your testing is both thorough and efficient. Dive into dataset management with confidence and precision!

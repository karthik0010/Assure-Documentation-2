 # Datasets

 A dataset serves as a structured system that organizes and groups created variables, allowing for efficient data management and categorization in a unified manner. This is used to override the default value of a variable with new one. This is useful when testing a scenario with multiple data. In AssureQA, user can call the dataset directly to the testcase from testcase editor/suite node editor of the test flow or through the for loop.

 ## Creating Dataset

 1. Click on Global menu 
 
 2. Click on Datasets section 
 
 3. Click on Create dataset button 

 ![d1](/DatasetImages/d1.png)

 4. Type a dataset name
 
 5. Click on create
 
 ![d2](/DatasetImages/d2.png)

 **Adding override values manually**

 6. Click on add row, select desired variables
 
 ![d4](/DatasetImages/d4.png)
 
 7. Enter a value which can be a plaintext/built-in function to the override value's fields
 
 ![d5](/DatasetImages/d5.png)

 8. To add built-in function, click on the definition field of override value column, click on '*f*' button,click on builtin functions, select required function, fill all fields and then click on add.
 
 ![d6](/DatasetImages/d6.png)

 Added function will be displayed on the field.
 
 ![d7](/DatasetImages/d7.png)
 
 9. Click on add column, add required number of override value columns
 
 ![d8](/DatasetImages/d8.png)
 
 ![d9](/DatasetImages/d9.png)
 
 10. Click on update
 
 ![d10](/DatasetImages/d10.png)
 
 **Adding override values using Csv/.xlsx file**
 
 10. Click on kebab menu
 
 11. Click on export csv
 
 ![d11](/DatasetImages/d11.png)
 
 12. Open the dowloaded file
 
 13. Enter values below the variable name (note: If we want to give built-in functions through csv, it must be written in a specific format like {{functionname(value)}}, for e.g, {{randomNum(11)}} on the sheet).
 
 ![d12](/DatasetImages/d12.png)

 14. Save the file
 
 15. Back to AssureQA's dataset editor, click on kebab menu and select import csv
 
 ![d13](/DatasetImages/d13.png)
 
 16. Click on upload file box and choose the edited file from computer 
 
 ![d14](/DatasetImages/d14.png)

 17. Click on upload button.
 ![d15](/DatasetImages/d15.png)
 
 New override value columns will be added or value will be filled into the existing columns based on the edits made on the csv.

 ![d16](/DatasetImages/d16.png)
 
 18. Click on update.

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

 Note: In the first method, the variables of the test case will be overridden using only the values from the first override value column, while the other columns are ignored.


 **Adding Dataset to Test Flow**

 We can use dataset in two ways inside a testflow. One way is applying it directly to the testcase listed in suite node editor and other way is applying it only to the shared steps i.e, via For Loop. First method's steps are mentioned below and for the other one, please refer 'for loop' section.

 1. Goto test flowpage.
 
 2. Create a flow
 
 3. Add suite node and add testcase which contains variables same as that in the created dataset.
 
 4. Click on the dataset dropdown button near each added testcase in the suite node editor.
 
 ![d20](/DatasetImages/d20.png)
 
 5. Select created dataset and the selected one's name will be shown on the field.

![d21](/DatasetImages/d21.png)

![d22](/DatasetImages/d22.png)

Note: In the first method, the variables of the test case will be overridden using only the values from the first override value column, while the other columns are ignored.

**Update Dataset**

If any change is needed for the created dataset. The user has an option to edit and update the set. Let’s see how this can be done.


1. Click on dataset tab of the global menu

2. Click on the three dots (meat balls) button near the created dataset

3. Select update from the options

![d23](/DatasetImages/d23.png)

4. After making required changes, click on Update button

![d24](/DatasetImages/d24.png)

**Delete Dataset**

If the dataset is unnecessary, it can be deleted or removed. Let’s see how a dataset can be deleted.

1. Click on the meat balls button

2. Click on delete

![d25](/DatasetImages/d25.png)

3. Click Delete button from the confirmation box

![d26](/DatasetImages/d26.png)

Hence the dataset will be deleted.

**Dataset Filter**

AssureQA allows users to find a particular dataset from among multiple datasets either by search or by using maintainer filter.

![d27](/DatasetImages/d27.png)

The highlighted portion in the image showcases the available filters within the Dataset. These filters help users to: choose a Maintainer to access created datasets, search for specific one by their names, and use the reset button to reset the filter settings as needed.

**Navigation**

Users have the ability to navigate to other pages using this option.

![d28](/DatasetImages/d28.png)

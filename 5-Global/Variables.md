
# Variables

Variables are containers for storing data values. Variables are a highly advantageous feature in Assureqa. Employing variables in your test cases eliminates the necessity of duplicating test cases, resulting in significant time saving. Users have the ability to create variables that hold diverse data types, encompassing plain text, as well as built-in functions for generating random numbers, randomalpha, randomalpha number, customdate, customtime, range and increment.

**Creating variables**

Go to Global, click on 'Create Variable'.

![Var1](/VariablesImage/var1.png)

A dialog box will appear, prompting the user to input the variable name and its definition. The definition can be plaintext or built-in function. The plaintext may include numbers, alphabetic characters, special characters, etc., based on the user's choice. Once both the variable name and definition are entered, the user can proceed by clicking the "create" button.

![var2](/VariablesImage/v2a.png)

To create a variable using a built-in function, open the "Create Variable" pop-up, click on the "Definition" field, and then click the "*f*" button. 

![var3](/VariablesImage/v3a.png)

It will opens to a new dialog box which will list all the available built-in functions such as random numbers, random alpha, random alphanumber, custom date, custom time, and range. Users can choose the desired function based on their preferences. Once the desired built-in function is selected, proceed by clicking the "add" button.

![var4](/VariablesImage/var4.png)

Selected built-in function will appear on the definition field, then click on create button to complete the process. 

![var5](/VariablesImage/v5a.png)

Multiple inputs can be utilized in the definition field according to the user preference.

![var6](/VariablesImage/v6a.png)

**Types of Built-in function**

****Randomnum()****

Randomnum refers to a function that generates a random numerical value. Users can give desired number as input in the "number of digits" field.

![var7](/VariablesImage/var7.png)

When we click on the 'number of digits' field, up-down arrow buttons will appear which helps the user to increase/decrease the value at the field.

Expected outcome based on input will be displayed as 'example'.

****Randomalpha()****

Randomalpha generates alphabets randomly, depending on the length specified by the user for the string. Users can give desired number as input in the "Length of string" field. 

![var8](/VariablesImage/var8.png)

When we click on the 'Length of string' field, up-down arrow buttons will appear which helps the user to increase/decrease the value at the field.

Expected outcome based on input will be displayed as 'example'.

****Randomalphanum()****

Randomalphanum refers to a function that generates alphanumeric characters randomly, depending on the length specified by the user for the string.

Users can give desired number as input in the "Length of string" field. 

![var9](/VariablesImage/var9.png)

When we click on the 'Length of string' field, up-down arrow buttons will appear which helps the user to increase/decrease the value at the field.

Expected outcome based on input will be displayed as 'example'.

****CustomDate()****

Customdate refers to a function that allows users to generate a date based on specific parameters such as day, month and year. 

User can type a desired format by referring the "date format reference" link, into the the "date format" field.

Users can give desired number as input in the "Offset in Days" field. 

![var10](/VariablesImage/var10.png)

When we click on the 'Offset in Days' field, up-down arrow buttons will appear which helps the user to increase/decrease the value at the field.

Expected outcome based on input given will be displayed as 'example'.

****Customtime()****

Customtime refers to a function that allows user to generate a time based on specific parameters such as hours, minutes, and seconds. 

User can type a desired format by referring the "Time format reference" link, into the the "Time format" field.

Users can give desired number as input in the "Offset in minutes" field. 

![var11](/VariablesImage/var11.png)

When we click on the 'Offset in minutes' field, up-down arrow buttons will appear which helps the user to increase/decrease the value at the field.

Expected outcome based on input given will be displayed as 'example'.

****Range ()****

Range denotes a function that generates random values within a specified range.

Users must give desired number as input in the "from" field. 

![var12](/VariablesImage/var12.png)

When we click on the 'from' field, up-down arrow buttons will appear which helps the user to increase/decrease the value at the field.

Users must give desired number as input in the "To" field also, inorder to complete the process. 

Expected outcome based on input given will be displayed as 'example'.

****Increment()****

Increment denotes a function that increment a number.

Users must give desired number as input in the "from" field. 

![var13](/VariablesImage/var13.png)

When we click on the 'from' field, up-down arrow buttons will appear which helps the user to increase/decrease the value at the field.

Users must give desired number as input in the "Increment by" field also, inorder to complete the process. 

Expected outcome based on input given will be displayed as 'example'.

**Creation of secret type variable (data masking)**

Assure QA provides a provision to mask or encrypt the testdata inside a variable to prevent disclosure of sensitive data like secret passwords during testing. The steps below says 

how to create a secret type variable:

 1. Select Global menu.
 2. Click on "create variable" button.
 3. Enter variable name at the name field.
 4. Enter data to the definition field.
 5. Click on check box near 'Contains password or secret?'.

![var14](/VariablesImage/var14.png)

 6. Click on create button.

![var15](/VariablesImage/var15.png)

All the created variables will be displayed on the variables page, and users can filter variables based on maintainers or conduct searches using the variable name. 

![var16](/VariablesImage/var16.png)

AssureQA also allows the users to  update and delete the created variables.

**Updating variables**

 1. Goto variables page.
 2. Clicking on the three dots (meat balls button) which will display two options like "Update" and "Delete."

![var19](/VariablesImage/var19.png)

 3. Click on update, a pop-up showing variable editor will be displayed.
 4. Change variable name or value, then click on update button.

![var20](/VariablesImage/var20.png)

**Deleting variables**

 1. Goto variables page.
 2. Clicking on the three dots (meat balls button) which will display two options like "Update" and "Delete."
 3. Click on delete, a pop-up asking confirmation will be displayed.

![var21](/VariablesImage/var21.png) 
 
 4. Click on delete button.
 
 ![var22](/VariablesImage/var22.png)

### Using variables to the teststep in a test case

Inside keyword definition field:

1. In  Test Case editor page, click on the step which will open the step config.
2. Click on the definition field and then on the '</>' button.

![var23](/VariablesImage/var23.png)

3. Hover over the variables, search and/or select desired variable from the list.

![var24](/VariablesImage/var24.png)

4. Selected variable will be displayed on field.

![var25](/VariablesImage/var25.png)

5. Click on save.

![var26](/VariablesImage/var26.png)

Inside locator field:

 1. In  Test Case editor page, click on the step which will open the step config. 
 2. Click on '+' button near Locator section.
 3. Click on new definition.

 ![var27](/VariablesImage/var27.png)

 4. Click on the definition field and then on the '{ }' button.
 5. Hover over the variables, search and/or select desired variable from the list.
 6. Selected variable will be displayed on field.
 
 ![var 28](/VariablesImage/var28.png)

 7. Click on save.

Inside javascript editor:

 1. In  Test Case editor page, click on the step like customwdio which will open the step config.
 2. Click on Javascript Editor.
 3. Type js code and to use the names of our created variables in the code use the following format: `&{{variable name}}`.
  
 ![var29](/VariablesImage/var29.png)

 4. Click on save.

### Using variables to the teststep in a shared test

Inside keyword definition field:

1. In  shared test editor page, click on the step which will open the step config.
2. Click on the definition field and then on the '</>' button.
3. Hover over the variables, search and/or select desired variable from the list.
4. Selected variable will be displayed on field.
5. Click on save.

![var30](/VariablesImage/var30.png)

Inside locator field:

 1. In shared test editor page, click on the step which will open the step config. 
 2. Click on '+' button near Locator section.
 3. Click on new definition.
 4. Click on the definition field and then on the '{ }' button.
 5. Hover over the variables, search and/or select desired variable from the list.
 6. Selected variable will be displayed on field.
 
 ![var31](/VariablesImage/var31.png)

 7. Click on save.

Inside javascript editor

 1. In  shared test editor page, click on the step which will open the step config.
 2. Click on Javascript Editor.
 3. Type js code and to use the names of our created variables in the code use the following format: **`&{{variable name}}`**.
 
 ![var32](/VariablesImage/var32.png)

 4. Click on save.

**Using build-in function in the testcase**

 1. Go to testcase page and select the required testcase
 2. Click on the desired test step.
 3. To add build –in function to the definition field, remove/keep the existing definitions then click on the '</>' button.
 
 ![var33](/VariablesImage/var33.png)

 4. Click on built-in functions, select desired one and fill all required fields. 
 5. Click on add button. 
 6. Click on save

**Using build-in function in the sharedtest**

 1. Go to testcase page, select shared steps tab and open the required shared test
 2. Click on the desired test step.
 3. To add build –in function to the definition field, remove/keep the existing definitions then click on the '</>' button.

![var34](/VariablesImage/var34.png)

 4. Click on built-in functions, select desired one and fill all required fields. 
 5. Click on add button. 
 6. Click on save

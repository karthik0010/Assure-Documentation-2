# 🚀 API Testing with AssureQA

AssureQA enables you to create, execute, and manage API tests, specifically supporting RESTful API testing. RESTful APIs provide access to resources using standardized methods and protocols, simplifying the development and maintenance of applications.

---

## 📂 Collection Management

### **Creating a Folder**

1. Click on the '**+**' button.
2. Select **New Folder**.

   ![api1](/images/api1.png)

3. Enter the folder name and select the parent folder.
4. Click **Create**.

   ![api2](/images/api2.png)

Created folders will be displayed on the left-hand side.

   ![api3](/images/api3.png)

### **Renaming a Folder**

1. Click on the **kebab menu** next to the folder.
2. Select **Rename**.

   ![api4](/images/api4.png)

3. Enter the new name in the **Name** field.
4. Click **Update**.

   ![api5](/images/api5.png)

### **Creating a Subfolder**

1. Click on the **kebab menu** next to the folder.
2. Select **New Folder**.

   ![api6](/images/api6.png)

3. Enter the folder name and select the parent folder.
4. Click **Create**.

### **Deleting a Folder**

1. Click on the **kebab menu** next to the folder.
2. Select **Delete**.

   ![api7](/images/api7.png)

3. Click **Delete** in the confirmation dialog box.

   ![api8](/images/api8.png)

---

## 🔄 Sending API Requests

### **Creating a New Request Inside a Folder**

1. Click on the **kebab menu** of the folder.
2. Select **New Request** from the options.
3. Enter the request name.
4. Click **Create**.

   ![api9](/images/api9.png)

The request editor will be displayed on the right.

   ![api10](/images/api10.png)

### **Saving a New Request to an Existing Folder**

1. Click on the '**+**' button at the top-right corner.

   ![api11](/images/api11.png)

2. Click on **Save**.

   ![api12](/images/api12.png)

3. Enter the request name.
4. Select the folder by clicking on its name.
5. Click **Save**.

   ![api13](/images/api13.png)

The saved request will be displayed inside the folder.

   ![api14](/images/api14.png)

---

## 🚀 Sending a Request

1. Click on the required request in the folder.
2. Click on the **method** dropdown near the URL field. Select the desired HTTP method (GET, POST, PUT, DELETE, PATCH). The default method is GET.

   ![api15](/images/api15.png)

3. Enter the URL.
4. Click **Send** to send the request to the server.

   ![api16](/images/api16.png)

---

## 📋 Viewing the Response

The server's response will be displayed in the response pane, where you can view:

- **JSON**: Automatically formatted and indented for readability.
- **Raw**: Displays the unformatted response.
- **Headers**: Metadata about the response.
- **Test Result**: Displays the outcomes of any tests you've written to validate the API response.

   ![api42](/images/api42.png)

---

## 🔧 Sending Data with HTTP Requests

### **Adding Parameters**

1. Navigate to the request configuration section.
2. Click on **Params**.
3. Enter key-value pairs as needed.

   ![api18](/images/api18.png)

4. To unselect or delete added key-values, use the green tick or red bin icons.

   ![api19](/images/api19.png)

---

### **Configuring the Request Body**

1. Choose a method (POST, PUT, PATCH).
2. Select the content type (JSON, XML, etc.).
3. Enter or upload the required data.

   ![api21](/images/api21.png)

---

### **Adding Headers**

1. Open the **Headers** configuration.
2. Add or modify key-value pairs for the headers.

   ![api22](/images/api22.png)

3. To unselect or delete headers, use the green tick or red bin icons.

   ![api23](/images/api23.png)

---

## 🔒 Authorization

1. Access the **Authorization** settings.
2. Choose the authorization type (Bearer Token, Basic Auth).
3. Enter the required credentials or tokens.

   ![api25](/images/api25.png)

---

## 🧪 Writing Test Scripts

1. Open a request and click on the **Test** section.
2. Write test scripts using JavaScript or click on **Snippet** for code examples.

   ![api26](/images/api43.png)

3. Save and send the request.
4. Review the test results.

---

## 🌍 Environment and Global Variables

### **Creating Global Variables**

1. Click on the **Environment** menu and select **Global Variables**.
2. Click **+** to add a new variable.
3. Enter the key-value pairs and click **Save**.

   ![api38](/images/api38.png)

---

### **Creating Environment Variables**

1. Click on the **Environment** menu and select **+** to create a new environment.
2. Enter a name (e.g., Development) and click **Create**.
3. Add key-value pairs for the environment variables.

   ![api31](/images/api31.png)

4. Use the variables in your request by inserting them into the URL field as `{{variablename}}`.

---


By following these steps, you can effectively create, execute, and manage API tests in AssureQA. Dive into the world of API testing and make your testing process more efficient!

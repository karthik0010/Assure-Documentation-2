# 🚀 API Testing with AssureQA

AssureQA enables you to create, execute, and manage API tests, specifically supporting RESTful API testing. RESTful APIs provide access to resources using standardized methods and protocols, simplifying the development and maintenance of applications.

---

## 📂 Collection Management

### **Creating a Collection**

1. Click on the '**+**' button.
2. Select **New Collection**.

   ![api1](/images/col1.png)

3. Enter the collection name and select the parent folder.
4. Click **Create**.

   ![api2](/images/col2.png)

Created collections will be displayed on the left-hand side.

   ![api3](/images/api3.png)

### **Renaming a Collection**

1. Click on the **kebab menu** next to the collection.
2. Select **Rename**.

   ![api4](/images/col3.png)

3. Enter the new name in the **Name** field.
4. Click **Update**.

   ![api5](/images/api5.png)

### **Creating a Sub-collection**

1. Click on the **kebab menu** next to the collection.
2. Select **New Collection**.

   ![api6](/images/col5.png)

3. Enter the collection name and select the parent folder.
4. Click **Create**.

### **Deleting a Collection**

1. Click on the **kebab menu** next to the collection.
2. Select **Delete**.

   ![api7](/images/col6.png)

3. Click **Delete** in the confirmation dialog box.

   ![api8](/images/col7.png)

---

## 🔄 Sending API Requests

### **Creating a New Request Inside a Collection**

1. Click on the **kebab menu** of the collection.
2. Select **New Request** from the options.
3. Enter the request name.
4. Click **Create**.

   ![api9](/images/api9.png)

The request editor will be displayed on the right.

   ![api10](/images/api10.png)

### **Saving a New Request to an Existing Collection**

1. Click on the '**+**' button at the top-right corner.

   ![api11](/images/api11.png)

2. Click on **Save**.

   ![api12](/images/api12.png)

3. Enter the request name.
4. Select the Collection by clicking on its name.
5. Click **Save**.

   ![api13](/images/api13.png)

The saved request will be displayed inside the collection.

   ![api14](/images/api14.png)

---

## 🚀 Sending a Request

1. Click on the required request in the collection.
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


## Interceptor

AssureQA offers two interceptors like Browser and Proxy to intercept API requests and responses for testing purposes.
Browser-Directly sents request from browser to server.
Proxy- Proxy server acts as an intermediary between the client (like a web browser) and the server. It forwards 
client requests to the server and sends the server's response back to the client. 
User can select either of them for testing.

![api27](/images/api27.png)

---

## 🌍 Environment and Global Variables

**Global Variables**
Global variables in Assureqa are variables that are accessible across all collections, environments, and requests within your Assureqa workspace. They are useful when you need to reuse values across different requests and collections without needing to define them separately each time. The following steps outline the process for creating and utilizing global variables in the request.

1. Click on environment menu

![api28](/images/api28.png)

2. Click on global variables in Assureqa.
3. Click on '+' near search field

![api37](/images/api37.png)

4. Enter key 
5. Enter value
6. Click on save

![api38](/images/api38.png)

7. To unselect the added key-value, click on green tick button.

![api39](/images/api39.png)

8. To delete the added key-value, click on red bin button.

![api40](/images/api40.png)

9. Go to request, paste the global variable in the url field in the form: {{variablename}}.

10. If the environment is selected, the variable remains in red color. To unselect the environment, click on "environment" dropdown button and select "no environment" from the list.

11. When we unselect environment, the variable color changes to green.

![api41](/images/api41.png)

12. Click on save and then send the request.

**Environment Variables**
Environment variables in Assureqa are used to manage dynamic data and simplify the process of testing APIs across different environments. They allow you to store and reuse values such as URLs, API keys, or tokens across multiple requests, making your testing process more efficient and organized. The following steps outline the process for creating and utilizing environment variables in the request.

1. Click on the Environments in Assureqa that appear upon clicking the enviroment menu.
2. Click on '+' near the environment 

![api29](/images/api29.png)

3. Enter a name (e.g., "Development").
4. Click on create, created environment will be displayed on left hand side.

![api30](/images/api30.png)

5. Click on '+' near search field
6. Enter key 
7. Enter value
8. Click on save

![api31](/images/api31.png)

9. To unselect the added key-value, click on green tick button.

![api32](/images/api32.png)

10. To delete the added key-value, click on red bin button.

![api33](/images/api33.png)

11. Go to request, paste the environment variable in the url field in the form: {{variablename}}.
12. If the environment is not selected, the variable remains in red color. To select environment, click on "no environment" dropdown button and select one from the list.

![api34](/images/api34.png)

![api35](/images/api35.png)

13. Selected environment will be displayed and the variable color changes to green which means that variable belongs to the selected environment.

![api36](/images/api36.png)

14. Click on save and then send the request.

---


By following these steps, you can effectively create, execute, and manage API tests in AssureQA. Dive into the world of API testing and make your testing process more efficient!

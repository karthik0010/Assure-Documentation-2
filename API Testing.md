# API Testing

AssureQA enables you to create, execute, and manage API tests within the platform, specifically supporting RESTful API testing. RESTful APIs provide access to resources using standardized methods and protocols, simplifying the development and maintenance of applications.

## Collection

**Creating folder**
 1. Click on '**+**' button
 2. Click on new folder
 
 ![api1](/images/api1.png)

 3. Enter folder name and select parent folder
 4. Click on Create

![api2](/images/api2.png)

Created folder will be displayed on the left hand side.

![ap3](/images/api3.png)

**Renaming folder**
 
 1. Click on kebab button of the folder
 2. Click on rename option
 
 ![api4](/images/api4.png)

 3.  Enter new name to the 'name' field
 4. Click on update

![api5](/images/api5.png)


**Creating sub folder**
 1. Click on kebab button of the folder
 2. Click on new folder

![api6](/images/api6.png)

 3. Enter folder name and select parent folder
 4. Click on Create

**Deleting folder**
 1. Click on the kebab button near the created folder
 2. Click on delete button

 ![api7](/images/api7.png)

 3. Click on delete on the confirmation box 

![api8](/images//api8.png)

## Sending API request

**Creating new request inside the folder**

 1. Click on the kebab button on the folder
 2. Select "new request" from options
 3. Enter request name
 4. Click on the create
 
 ![api9](/images/api9.png)

 Request editor will be displayed on the right.

 ![api10](/images/api10.png)

**Saving a new request to existing folder**
 
 1. Click on the '+' at the top right corner
 
 ![Api11](/images/api11.png)

 2. Click on save

 ![api12](/images/api12.png)
 
 4. Enter request name
 5. Select folder by clicking on the folder name
 6. Click on save

![api13](/images/api13.png)

Saved request will be displayed inside the folder.

![api14](/images/api14.png)
 
 **Sending request**

After creating a request, the next step is to know how to use these requests for API testing. Let's go through it step by step.
 
 1. Click on the required request in the folder
 2.  Click on method dropdown near the url field, it will display all available http methods like GET, POST, PUT, DELETE and PATCH. By default, the method will be GET.

 ![api15](/images/api15.png)

 3. Select a desired method, let it be GET.
 4. Click on the url field, remove the dummy url and add required url.
 5. Click on send inorder to send request to the server.

![api16](/images/api16.png)

  **Response from server**

After sending the request, the response from the server will be displayed in the response pane.
User can view the response and check the correctness of API responses. An API response consists of the response body as JSON and raw headers,and the HTTP status code. Also the details about the response, including test results, response size and response time.
 

JSON

In JSON format, Assureqa automatically formats and indents the response data, making it easier to read.
JSON view also highlights different elements such as keys, values, and data types with distinct colors, which helps in quickly identifying various parts of the response. User can collapse and expand nested objects or arrays for easier navigation.

Raw

The Raw view shows the response exactly as it was received from the server, without any additional formatting or indentation. This view is useful if the response is not JSON, such as plain text, HTML, XML, or other formats. It displays the entire response content as a single string of text. The Raw view is handy when you need to see the exact data sent by the server, including any formatting or line breaks.

Headers

Response Headers are the headers sent by the server in response to your request. They provide metadata about the response, such as content type, content length, server information, and caching directives. You can view these in the "Headers" tab in the response section.

Test Result

Assureqa allows you to write test scripts in JavaScript that run after the response is received. These tests can check various conditions, such as status codes, response times, or specific data in the response body.
The results of these tests are shown under the "Test Result" tab. If all tests pass, you'll see green mark; if any tests fail, you'll see red mark. In simple words we can say, that the Test Result tab shows the outcomes of any tests you’ve written to validate the API response.


![api42](/images/api42.png)

**Send data along with HTTP requests**


Middleware in API testing is crucial for managing various aspects of your API requests and responses, including parameters, request bodies, authentication, and test configurations. Here’s how you can handle each of these elements in your system:
  
Params

Parameters are essential for customizing your API requests and can be used to filter, sort, or modify the behavior of the API. They can be passed in Query Parameters which are added to the URL to filter or sort results. For example, `GET /api/users?page=1`.


How to Add Parameters?

 1. Navigate to the request configuration section.
 2. Click on the params
 3. Enter the key-value pairs as needed.

 ![api18](/images/api18.png)

4. To unselect the added key-value, click on green tick button.

![api19](/images/api19.png)

5. To delete the added key-value, click on red bin button.

![api20](/images/api20.png) 

Request Body

The request body is used to send data to the server in POST, PUT, or PATCH requests. It can be formatted in different ways: JSON, XML, Form Data, html, plain etc.

How to configure the Request Body?

1. Choose the request method (POST, PUT, PATCH).
2. Select the content-type.
3. Enter or upload the data as required.

![api21](/images/api21.png)

Headers

Headers provide additional information about the request or response.

How to configure Headers?

1.  Open the headers configuration section.
2.  Add or modify header fields as needed.
3. Specify key-value pairs for each header.

![api22](/images/api22.png)

4. To unselect the added key-value, click on green tick button.

![api23](/images/api23.png)

5. To delete the added key-value, click on red bin button.

![api24](/images/api24.png)

Authorization

Authorization ensures that the API request is made by an authorized user. Common methods include:
Bearer Token: Sent in the authorization header.
Basic Auth: Encoded credentials in the authorization header.

How to Set Up Authorization?

1. Access the authorization settings.
2. Choose the authorization type (none, Bearer Token, Basic Auth).
3. Enter the required credentials or tokens.

 ![api25](/images/api25.png)


Tests

In Tests, code written in the test section of the request will be executed after the response is received. This is useful for validating 
response data or status codes. Assure qa also provides code snippet.

![api26](/images/api26.png)

How to write Test scripts?

1. Open a request
2. Click on the test
3. Write test scripts using the scripting language on the test section or click on snippet at the right hand side

![api26](/images/api43.png)

4. Click on Save and send the request
5. Review the results

## Interceptor

AssureQA offers two interceptors like Browser and Proxy to intercept API requests and responses for testing purposes.
Browser-Directly sents request from browser to server.
Proxy- Proxy server acts as an intermediary between the client (like a web browser) and the server. It forwards 
client requests to the server and sends the server's response back to the client. 
User can select either of them for testing.

![api27](/images/api27.png)

## Environment and Global Variables

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


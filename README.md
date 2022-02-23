# **DATA GATHERING**
As a data analyst, obtaining hight quality data should be priority. Data can be classified into 2 main types:  
- **Primary:** data you have created. e.g conducting a survey.
- **Secondary:** data acquired from a third party.


Data is usually available online in downloadable files such as: .csv and .xlxs. There are 2 methods in which you can obtain data that is available online, but is not packaged in a downloadable file: 
1. **Web scraping:** involves extracting information programatically from a website. This method involves:
- Requesting the webpage from a server.
- Extracting the relevant data from the HTML document that is sent to you.


2. **API (Application Programming Interface):** specifies how software components should interract. You may consider it as a contract between a client and a server. If the client makes a request in a specific format, the server will always respond in a documented format.

**In this research, we will be dealing with web-based API's, but the concept of API's exist in other forms.**


## **HTTP REQUESTS (Hyper text transfer protocool)** 
It specified how requests and responses are to be formatted and transmitted.

Websites consists of a couple of files: the HTML code for the webpage and other supplimentary resources such as images, videos, styles etc.

The files are stored in a remote machine somewhere called server. When surfing, all we are doing is downloading these files to our computer and using the browser to display them properly. That is done by making a request. 
We send a request to the server indicating we want to obtain a certain file. The server then processes this request then responds accordingly.

There are 2 most popular HTTP request types.
- **GET request:** used to obatain data from a server. It is not used for sensitive information.

- **POST request:** used when you want to send sensitive or confidential information. login credentials and passwords are transmitted through a post request

**STATUS CODE:** the most common status codes are: 200(processed successfully) and 404(missing webpage).

If everything is ok with the request and you get a 200 response, you will be able to extract the data sent with the response.


## **JSON (Java Script Object Notation)**
- It is a standard format for data exchange

- When Get requests are sent to API's, data is often returned as JSON.


It builds upon 2 structures
 - Dictionaries: contains key value pairs surrounded by curly brakcets. The key value of each pair is signified after a colon, and the pairs are searated by commas.
 
 {key1: value1,
  key2: value2}
  
  - Lists: Collection of items. It is contained in square brackets []. 


**In this research, we will be dealing with API's gotten from https://mixedanalytics.com/blog/list-actually-free-open-no-auth-needed-apis/**

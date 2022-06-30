# Product
Low code api design and implementation using open source spring framweork
1.	HelloWorld  Example 
Description : 
In this simple example we are using a rest call to display the input string message as “Hello world”. If we change the input string then accordingly the same msg will be shown in the output . . For example use the http post method to send the input json as 
{
“msg”:”Hello World”
} 
The output will be json 
{
“input_msg” :”Hellow World”
}

Workflow:

2.	Greeting Example : This example show concatenation operation between two string one from input and one which is default or hard coded string. SO we have the http post service with input body as json
{
“personName”:”John”
}
The ouput will be json
{
“Greeting”: “Welcome to the new community John”
}

3.	Fetch data from end system - database : This example shows how we can fetch data from database. Database is pre-configured. We pass the table name from which we need to get the data .
4.	Fetch data from end system - file : This example shows how we can fetch data from external file. 
5.	Fetch filtered data from end system – database : This example shows how we can fetch data from database. Database is pre-configured. We pass the table name as well as filter criteria to get the data .
6.	Fetch filtered data from end system – file : This example shows how we can fetch data from external file. We pass the file name as well as filter criteria to get the data .
7.	Insert single record into database : This example shows how we insert single record into database according to the input body in  post request as json. 
8.	Update single record from database : This example shows how we update single record from database according to the record id passed in the URI parameter with post request and the updated values in the body json
9.	Delete single record from database : This example shows how we delete single record from database according to the record id passed in the URI parameter with delete request. 
10.	Fetch data from end system – MQ : This example shows how we can fetch data from messaging queue. We pass the queue name to get the data .
11.	Iterate over a collection (ForEach) : This example shows how we can iterate over a collection using single threaded synchronous For-Each and get a specific data set .
12.	Iterate over a collection (Parallel- Asynchronous) : This example shows how we can iterate over a collection using multiple  asynchronous parallel  thread and get a specific data set .
13.	Single decision based routing (if-else) : This example shows how we can route to different functions depending on the decision to get a specific data set .
14.	Choice based routing: This example shows how we can route to different functions depending on the multiple decision to get a specific data set .
15.	Scheduled polling of end system : This example shows how we can have our flow triggered automatically after a fixed frequency to perform a particular function to get a specific data.
16.	Event based flow trigger – Database  : This example shows how we can have our flow triggered automatically when we have an new record inserted or updated in the database.
17.	Event based flow trigger – File  : This example shows how we can have our flow triggered automatically when we have an new file added to the remote directory.
18.	DataTransformation DB To Json : This example shows how we can get single record from database and transform it to JSON.
19.	DataTransformation XML To Json : This example shows how we can transform xml data to JSON.
20.	DataTransformation CSV To Json : This example shows how we can transform xml data to JSON.
21.	External Rest Service : This example shows how we can call external rest web service and show the data .


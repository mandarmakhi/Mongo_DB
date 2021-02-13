![](https://img.shields.io/github/followers/mandarmakhi?label=Follow%40mandarmakhi&style=social)
![](https://img.shields.io/github/forks/mandarmakhiMongo_DBe?label=Fork&style=social)
![](https://img.shields.io/github/stars/mandarmakhi/Mongo_DB?style=social)
![](https://img.shields.io/github/watchers/mandarmakhi/Mongo_DB?style=social)
![](https://img.shields.io/github/issues/mandarmakhi/Mongo_DB)
![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://mandarmakhi.github.io/Mongo_DB/)]
![](https://img.shields.io/github/repo-size/mandarmakhi/DataScience-R-code)
![](https://img.shields.io/github/languages/code-size/mandarmakhi/Mongo_DB)


# Mongo_DB ( NOSQL )

MongoDB is a source-available cross-platform document-oriented database program. Classified as a NoSQL database program, MongoDB uses JSON-like documents with optional schemas. 
MongoDB is developed by MongoDB Inc. and licensed under the Server Side Public License (SSPL).

Install MongoDB On Windows
To install MongoDB on Windows, first download the latest release of MongoDB from
[Click Here](https://www.mongodb.com/download-center).

![alt text](https://github.com/mandarmakhi/Mongo_DB/blob/master/Storage/Images/mongodb_cloud.jpg)

Enter the required details, select the Server tab, in it you can choose the version of MongoDB, operating system and, packaging as:

![alt text](https://github.com/mandarmakhi/Mongo_DB/blob/master/Storage/Images/mongodb_community.jpg)

Now install the downloaded file, by default, it will be installed in the folder C:\Program Files\.

MongoDB requires a data folder to store its files. The default location for the MongoDB data directory is c:\data\db. 
So you need to create this folder using the Command Prompt. Execute the following command sequence.

Open CMD Run The Command 

*C:\>md data*



*C:\md data\db*

In the command prompt, navigate to the bin directory current in the MongoDB installation folder. Suppose my installation folder is C:\Program Files\MongoDB

*C:\Users\Mandar>d:cd C:\Program Files\MongoDB\Server\4.2\bin*

*C:\Program Files\MongoDB\Server\4.2\bin>mongod.exe --dbpath "C:\data"*


This will show waiting for connections message on the console output, which indicates that the mongod.exe process is running successfully.

Now to run the MongoDB, you need to open another command prompt and issue the following command.

*C:\Program Files\MongoDB\Server\4.2\bin>mongo.exe*

MongoDB shell version v4.2.1
connecting to: mongodb://127.0.0.1:27017/?compressors=disabled&gssapiServiceName=mongodb
Implicit session: session { "id" : UUID("4260beda-f662-4cbe-9bc7-5c1f2242663c") }
MongoDB server version: 4.2.1

*>*

Mongo DB Installation Complete. Now  Next time when you run MongoDB, you need to issue only commands.

*C:\Program Files\MongoDB\Server\4.2\bin>mongod.exe --dbpath "C:\data"*

*C:\Program Files\MongoDB\Server\4.2\bin>mongo.exe*


***

1. [Create Database](https://github.com/mandarmakhi/Mongo_DB/blob/master/1.%20%20Create%20Database.ipynb)

2. [Drop Database](https://github.com/mandarmakhi/Mongo_DB/blob/master/2.%20%20Drop%20Database.ipynb)

3. [Create Collection](https://github.com/mandarmakhi/Mongo_DB/blob/master/3.%20%20Create%20Collection.ipynb)

4. [Drop Collection](https://github.com/mandarmakhi/Mongo_DB/blob/master/4.%20%20Drop%20Collection.ipynb)

5. [Datatypes](https://github.com/mandarmakhi/Mongo_DB/blob/master/5.%20%20Datatypes.ipynb)

6. [Insert Document](https://github.com/mandarmakhi/Mongo_DB/blob/master/6.%20Insert%20Document.ipynb)

7. [Query Document](https://github.com/mandarmakhi/Mongo_DB/blob/master/7.%20Query%20Document.ipynb)

8. [Update Document](https://github.com/mandarmakhi/Mongo_DB/blob/master/8.%20Update%20Document.ipynb)

9. [Delete Document](https://github.com/mandarmakhi/Mongo_DB/blob/master/9.%20Delete%20Document.ipynb)

10. [Projection](https://github.com/mandarmakhi/Mongo_DB/blob/master/10.%20Projection.ipynb)

11. [Limit Records](https://github.com/mandarmakhi/Mongo_DB/blob/master/11.%20Limit%20Records.ipynb)

12. [Sort Records](https://github.com/mandarmakhi/Mongo_DB/blob/master/12.%20Sort%20Records.ipynb)

13. [Indexing](https://github.com/mandarmakhi/Mongo_DB/blob/master/MongoDB%20Tutorial/13.%20Indexing.ipynb)

14. [Aggregation](https://github.com/mandarmakhi/Mongo_DB/blob/master/MongoDB%20Tutorial/14.%20%20Aggregation.ipynb)

15. [Create Backup](https://github.com/mandarmakhi/Mongo_DB/blob/master/MongoDB%20Tutorial/15.%20Create%20Backup.ipynb)

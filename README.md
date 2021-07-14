# Meal Info Service
#### By Sailash

## MongoDb Python Connection
    * Install required libraries.
    * Import required libraries.
    * To Create MongoClient object, pass the IP address or url of mongodb server and port number as argument to MongoClient class.
    * Pass database name as key for MongoClient object.
    * MongoDB will connect to the database if exists or create the database, and make a connection to it.

## Imported Library
1. Json
    * Read the data and convert to valied Json formate
2. pymongo
    * Tool for interacting with MongoDB database from Python

## PyMongo And MySQL Operations
1. find()
    * find() method is used to select documents that satisfies the criteria entered in a collection and return a cursor to the selected documents.
2. find_one()
    * findOne() method returns only one document that satisfies the criteria entered.
3. limit()
    * limit() function in MongoDB is used to specify the maximum number of results to be returned.
4. update_one()
    * updateOne() method updates a first matched document within the collection based on the given query.
5. update_many()
    * updateOne() method updates a n number of document within the collection based on the given query.
6. drop()
    * drop() method is used to drop a collection from a database.
7. delete_one()
    * deleteOne() method deletes the first document from the collection that matches the given selection criteria.
8. delete_many()
    * deleteOne() method deletes n number of document from the collection that matches the given selection criteria.
9. insert_one()
    * insertOne() inserts a single document into a collection.
10. insert_many()
    * insertMany() can insert multiple documents into a collection. Pass an array of documents to the method.
11. inserted_ids
    * inserted_ids will return the last inserted documents ids.
12. sort()
    * sort() method to sort the result in ascending or descending order.

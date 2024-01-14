# mongoDB
Learnings of MongoDB

**CRUD operations in MongoDB**

CREATE : insert document in COLLECTION
READ : Read document from COLLECTION
UPDATE : Update the document
DELETE : Delete the document

**Operators in MongoDB**

$and : AND Operator
$or : OR Operator
$lt : Less then Operator
$gt : Greater then Operator

**Dowload MongoDB Shell**
URL: https://www.mongodb.com/try/download/shell

**Queries**

**show dbs** / to see how many databases are there
**use Ecommerce** [database name]: when we use this query if the database name exist previously it will use that db otherwise it'll create the new one and will use that!
and again when we try to see our db using **show dbs** it won't appear in list because it has no collection. so,

**db.createCollection('Collection_name')** to create collection init use command

**db.Collection_name.countDocuments()** to check how many documents are there in the collection
**db.getCollectionNames()** to see the the the No.of collections are there in the DB
**db.Collection_name.insertOne({name: 'anil'})** to create Document in collection
**db.Orders.find()** to get all documents in that collection


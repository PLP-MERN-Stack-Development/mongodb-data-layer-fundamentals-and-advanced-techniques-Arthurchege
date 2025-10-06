PLP Bookstore – MongoDB Project
🗂️ Project Overview

This project was created as part of Week 1: MongoDB – Data Layer Fundamentals and Advanced Techniques.
It demonstrates how to build and manage a MongoDB database by performing CRUD operations, running advanced queries, using aggregation pipelines, and implementing indexing for performance improvement.

⚙️ Setup Instructions

1. Install MongoDB

Download and install MongoDB Community Edition from https://www.mongodb.com/try/download/community

OR

Use MongoDB Atlas (cloud version) at https://www.mongodb.com/cloud/atlas

2. Start MongoDB

If running locally, start the MongoDB service and open the MongoDB Shell using:

mongosh

3. Create the Database and Collection

In the shell:

use plp_bookstore
db.createCollection("books")

📘 Files Included
File Name Description
insert_books.js Script to insert at least 10 book documents into the books collection.
queries.js Contains all MongoDB queries (CRUD, advanced, aggregation, and indexing).
README.md Project documentation and setup instructions.
Screenshots file, showing the database and sample data in MongoDB Compass or Atlas.
🧾 Features Demonstrated

1. CRUD Operations

Insert, read, update, and delete book documents.

2. Advanced Queries

Filtering by genre, author, or year

Sorting by price (ascending/descending)

Projection to show specific fields

Pagination using limit() and skip()

3. Aggregation Pipelines

Average price of books by genre

Author with the most books

Group books by publication decade

4. Indexing

Single-field index on title

Compound index on author and published_year

Performance analysis using explain()

▶️ How to Run the Scripts

1. Insert Sample Data

In your Mongo shell:

load('insert_books.js')

2. Run Queries

Then run:

load('queries.js')

3. Verify in MongoDB Compass or Atlas

Open the plp_bookstore database and view the books collection.

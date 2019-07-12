
Motivation

I'll use this script to provide introduction to data analysis using SQL language, which should be a must tool for every data scientist - both for getting access to data, but more interesting, as a simple tool for advance data analysis. The logic behind SQL is very similar to any other tool or language that used for data analysis (excel, Pandas), and for those that used to work with data, should be very intuitive.

Feel free to respond with questions, and I'll try to explain more if need.
Important Definitions

SQL is a conceptual language for working with data stored in databases. In our case, SQLite is the specific implementation. Most SQL languges share all of the capabilities in this doc. The differences are usually in performance and advances analytical funcionalities (and sometimes bugs of course). Eventually, we will use SQL lunguage to write queries that would pull data from the DB, manipulate it, sort it, and extract it.

The most important component of the DB is its tables - that's where all the data stored. Usually the data would be devided to many tables, and not stored all in one place (so designing the data stracture propely is very important). Most of this script would handle how to work with tables. Other than tables, there are some other very useful concepts/features that we won't talk about:

    table creation
    inserting / updating data in the DB
    functions - gets a value as an input, and returns manipulation of that value (for example function that remove white spaces)


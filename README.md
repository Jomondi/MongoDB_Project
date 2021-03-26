# Exercise Description

      Using Pythong, create a MongoDB database connection to a database that resides in the Cloud and also local to your
      system - Show your python code and the collection structure (JSON format).

      Create two collections with the below schemas and upload data into the collections:

             a) Hospital:
                 hospital_id
                 hospital_name
                 bed-count
                 address
             b) Doctor:
                 doctor_id
                 doctor_name
                 hospital_id
                 date_joined
                 Speciality
                 Salary
                 experience

      Join these two collections and then print and display the records on the screen.


# Exercise Resolution

      The program is intended for the user to be able to create a database, collection and add data into the collections in MongoDB. 

      To first run the program, enter a username and password in the when calling the MongoClient.

      Description of the file:

          - Create the Healthcare database 

          - Create the Hospital collection

          - Create the Doctors collection

          - Run insert_data() function to insert data into the collections

          - Run cursor instance to join the tables and print out the values





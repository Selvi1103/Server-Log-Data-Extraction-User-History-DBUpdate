# Server-Log-Data-Extraction-User-History-DBUpdate

## Introduction:
    The task is to fetch data from a server log file, extract all email addresses along with their corresponding dates, and upload this data into a user history database. The goal is to ensure the extracted data is clean, accurate, and accessible for further analysis and historical tracking.

## Dataset :
  Attached in the repository

## Steps:

**Step 1: Extract Email Addresses and Dates**

  1. Read the log file and extract all occurrences of email addresses.
  2. Capture the date associated with each email address.


**Step 2: Data Transformation**

  1. Ensure the extracted data is structured in a format suitable for database insertion.
  2. Format the date into a standard format (e.g., YYYY-MM-DD HH:MM:SS).


**Step 3: Save Data to MongoDB**

  1. Save the processed data into a MongoDB collection named user_history.

**Step 4:Database Connection and Data Upload**

  1. Fetch the data from the MongoDB collection.
  2. Insert the data into a relational database (e.g., SQLite or any SQL database) using Python.
  3. The table name should be user_history.
  4. Include primary key constraints and any other relevant constraints.

**Step 5: Run Queries on the Database**

  1. Write and execute SQL  queries to analyze the data, :
  2. List all unique email addresses.
  3. Count the number of emails received per day.
  4. Find the first and last email date for each email address.
  5. Count the total number of emails from each domain (e.g., gmail.com, yahoo.com).



College_Project

Project Overview
College_Project is a Node.js application that demonstrates basic MySQL operations using the mysql2 package. It includes scripts for inserting records into faculty, library, and marks tables, displaying stored data, deleting specific rows, and querying selected fields.

Folder Structure
College_Project/ 
├── node_modules/ 
├── package.json 
├── package-lock.json 
├── dbcollege.js  
└── README.md

Installation Steps
1.Navigate to the project folder:
  cd College_Project
2.Install dependencies:
  npm install mysql2

Database Name
-college_db

Expected Outputs
faculty.js: Faculty Records Inserted Successfully
library.js: Library Records Inserted Successfully
marks.js: Marks Inserted Successfully
display.js: displays all rows from faculty, library, and marks using console.table() with headings
delete.js: prints the number of rows deleted for faculty, library, and marks
specific.js: displays selected columns from faculty, library, and marks using console.table()

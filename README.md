Student Registry System
A web app to manage student records.

Installation
Create Replit project: At replit.com, make a Node.js Repl named student-registry.

Add files: Create index.js, db.js, /public (with styles.css, HTML files), package.json, .gitignore, .replit. Copy provided files.

Set Secrets: In Replit, add:

DB_HOST: sql3.freesqldatabase.com
DB_USER: sql3776777
DB_PASSWORD: SzSrZv7FSt
DB_NAME: sql3776777
DB_PORT: 3306
Setup database: In phpMyAdmin (FreeSQLDatabase), run:

CREATE TABLE students (
id INT AUTO_INCREMENT PRIMARY KEY,
name VARCHAR(100) NOT NULL,
email VARCHAR(100) NOT NULL UNIQUE,
enrollment_date DATE NOT NULL
) ENGINE=InnoDB;

Install: In Replit shell: npm install.

Run: Ensure .replit has run = "npm run dev". Click “Run”.

Usage
Go to site

Add student: At /add_student.html, enter name (John Doe), email (john.doe@example.com), date (2023-10-01). Click Add Student.

View students: See list at /list_students.html.

Edit: Click Edit on list, update fields, click Update Student.

Delete: Click Delete on list, confirm.

Add to GitHub
Create repo: At github.com, make student-registry.

Push: In Replit shell:

git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/your-username/student-registry.git
git branch -M main
git push -u origin main

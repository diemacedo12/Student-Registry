<h1> Student Registry System </h1> 
<p> A web app to manage student records. </p>
<h2> Installation </h2>
<ul> <li> <b> Create Replit project </b>: At <a href="https://replit.com"> replit.com </a>, make a Node.js Repl named student-registry. 
</li> 
<li> <b> Add files </b>: Create index.js, db.js, /public (with styles.css, HTML files), package.json, .gitignore, .replit. Copy provided files. </li>
<li> <b> Set Secrets </b>: In Replit, add: 
<br>
<ul> <li> DB_HOST: sql3.freesqldatabase.com </li>
<li> DB_USER: sql3776777 </li> 
<li> DB_PASSWORD: SzSrZv7FSt </li> 
<li> DB_NAME: sql3776777 </li> 
<li> DB_PORT: 3306 </li></ul> </li>
<li>
<b> Setup database </b>: In phpMyAdmin (<a href="https://www.freesqldatabase.com"> FreeSQLDatabase </a>), run:
<br> CREATE TABLE students ( id INT AUTO_INCREMENT PRIMARY KEY, name VARCHAR(100) NOT NULL, email VARCHAR(100) NOT NULL UNIQUE, enrollment_date DATE NOT NULL ) ENGINE=InnoDB; </li>
<li> <b> Install </b>: In Replit shell: npm install. </li>
<li> <b> Run </b>: Ensure .replit has run = "npm run dev". Click “Run”. </li> </ul>
<h3> Usage </h3> <ul>
<li> <b> Go to site </b>: Go to site. </li>
<li> <b> Add student </b>: At /add_student.html, enter name (John Doe), email (john.doe@example.com), date (2023-10-01). Click Add Student. </li>
<li> <b> View students </b>: See list at /list_students.html. </li>
<li> <b> Edit </b>: Click Edit on list, update fields, click Update Student. </li>
<li> <b> Delete </b>: Click Delete on list, confirm. </li> </ul>
<h4> Add to GitHub </h4> <ul>
<li> <b> Create repo </b>: At <a href="https://github.com"> github.com </a>, make student-registry. </li>
<li> <b> Push </b>: In Replit shell: <br> git init git add . git commit -m "Initial commit" git remote add origin https://github.com/your-username/student-registry.git git branch -M main git push -u origin main
</li>
</ul>

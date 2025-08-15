# PHP Notes App

A simple PHP-based note-taking application using MySQL and mysqli.  
Users can create, edit, delete, and view notes with pagination support.

## Features
- Create new notes
- Edit existing notes
- Delete notes
- List notes with pagination
- Secure database queries using prepared statements
- MySQL database dump included (`notes_database.sql`)

## Installation

1. **Clone or download the project**
   ```bash
   git clone https://github.com/Homayuun/php-notes-app.git
   ```
   Or download the ZIP file from GitHub and extract it.

2. **Move the folder to MAMP’s `htdocs` directory**
   Place the project folder (e.g., `php-notes-app`) inside:
   ```
   Applications/MAMP/htdocs/
   ```

3. **Import the database**
   - Open MAMP and start the servers.
   - Go to phpMyAdmin:  
     [http://localhost/phpMyAdmin](http://localhost/phpMyAdmin)
   - Create a new database named `notes_database`.
   - Import the `notes_database.sql` file from the project.

4. **Open the project in your browser**
   Visit:  
   [http://localhost/php-notes-app/index.php](http://localhost/php-notes-app/index.php)

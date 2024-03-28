# Teachers Record Management System (TRMS)

## Introduction
The Teachers Record Management System (TRMS) is a project designed to manage records related to teachers. This document provides instructions on how to set up and run the TRMS project on your local web server.

## Installation Steps

1. **Download the zip file**: Obtain the zip file containing the TRMS project.

2. **Extract the file and copy the trms folder**: Extract the contents of the zip file and locate the 'trms' folder.

3. **Paste inside root directory**: Place the 'trms' folder inside the root directory of your web server. Depending on the web server you're using, this could be:
   - For XAMPP: `xampp/htdocs`
   - For WAMP: `wamp/www`
   - For LAMP: `var/www/html`

4. **Open PHPMyAdmin**: Go to your web browser and access PHPMyAdmin using the URL `http://localhost/phpmyadmin`.

5. **Create a database**: Inside PHPMyAdmin, create a new database with the name `trms`.

6. **Import trms.sql file**: Within the zip package, locate the `trms.sql` file inside the `SQL file` folder. Import this SQL file into the `trms` database you just created.

7. **Run the script**: Open your web browser and navigate to `http://localhost/trms` to access the frontend of the TRMS project.

## Credentials
- **Admin panel**:
  - Username: admin
  - Password: Test@123

- **Teacher panel**:
  - Username: jogoe12@yourdomain.com
  - Password: Test@123

Alternatively, you can register a new teacher if needed.

## Conclusion
Following these steps should allow you to set up and run the TRMS project on your local web server. For any issues or queries, feel free to reach out.

# Web-NLP-Task1
1-To create a remote control system using HTML, PHP, and SQL, you'll need the following components:
HTML: For creating the user interface.
PHP: For handling server-side logic and interacting with the database.
SQL: For storing and retrieving remote control instructions.

2-After clicking on any button, the remote_controls.php page will pop up and ensure that the process is successful,
followed by the value inserted.

3-here is the database named as smart. consistence of 3 columns

CREATE TABLE smart (
    id INT PRIMARY KEY AUTO_INCREMENT,
    direction VARCHAR(10) NOT NULL,
    timestamp TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

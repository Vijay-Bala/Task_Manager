# Task Manager CRUD Web Application

This project is a Task Manager web application developed using Flask, SQLite3, HTML, and CSS. It allows users to perform basic CRUD (Create, Read, Update, Delete) operations on tasks.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [License](#license)

## Installation

To get started with this project, follow these steps:

1. Clone the repository to your local machine:

``` bash
git clone https://github.com/Vijay-Bala/Task_Manager.git
```
2. Create a virtual environment (optional but recommended):
``` bash
python -m venv env
```
3. Activate the virtual environment:

- Windows: .\env\Scripts\activate
- MacOS/Linux: source env/bin/activate

4. Install the project dependencies:
``` bash
pip install -r requirements.txt
```

## Usage
Run the Flask application:
``` bash
python app.py
```
Open a web browser and navigate to http://localhost:5000 to access the Task Manager.

## Features
- Create, Read, Update, and Delete tasks.
- Sort tasks by priority, deadline, or status.
- Filter tasks by status (completed/uncompleted).
- Simple and intuitive user interface.

## Documentation

## Database Schema
- `id` (Integer, Primary Key): Unique identifier for each task.
- `content` (String) : Description of each task
- `completed` (Integer) : Status of completion
- `date_created`(Date) : Date of creation.

## Contributing
If you'd like to contribute to this project, please follow these steps:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and submit a pull request.

## License 
This project is licensed under the MIT License.

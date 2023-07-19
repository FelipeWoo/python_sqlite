# Python CRUD Operations with SQLite and Pandas

This repository contains a Python script that demonstrates CRUD (Create, Read, Update, Delete) operations with SQLite database using the `sqlite3` module. It also includes a Jupyter Notebook that showcases the usage of Pandas library to represent and manipulate the data from the SQLite database.

## Requirements

Make sure you have the following requirements installed:

- Python 3.9.2
- SQLite
- Jupyter Notebook

## Setup

1. Clone the repository:

   ```shell
   $ git clone https://github.com/yourusername/your-repo.git
   ```

2. Navigate to the project directory:

   ```shell
   $ cd your-repo
   ```

3. Create a virtual environment (optional but recommended):

   ```shell
   $ python3 -m venv venv
   ```

4. Activate the virtual environment:

   - For macOS/Linux:

     ```shell
     $ source venv/bin/activate
     ```

   - For Windows:

     ```shell
     $ venv\Scripts\activate
     ```

5. Install the required dependencies:

   ```shell
   $ pip install -r requirements.txt
   ```

Certainly! Here's the updated README file with the modified usage section:



## Usage

1. Run the Jupyter Notebook `python_sqlite3.ipynb` to perform CRUD operations on the SQLite database:

   ```shell
   $ jupyter notebook python_sqlite3.ipynb
   ```

   The notebook allows you to execute each cell to perform various CRUD operations on the SQLite database and see the results.

2. In the notebook, you can modify the queries and operations according to your needs and run the cells to interact with the SQLite database.

## Project Structure

The project has the following structure:

```
- python_sqlite3.ipynb    # Jupyter Notebook for SQLite CRUD operations
- database_file.db             # SQLite database file
- requirements.txt        # Dependencies file
```

- `python_sqlite3.ipynb`: Jupyter Notebook that contains the code for performing CRUD operations on the SQLite database.
- `database_file.db`: SQLite database file that stores the data.
- `requirements.txt`: Dependencies file that lists the required packages for the project.

Feel free to explore the notebook to understand the implementation and modify it according to your needs.


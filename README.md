# My-sqlite

## Table of contents

* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Prerequisites](#prerequisites)

## General info

My-sqlite program works as a functional SQL engine and CLI, with the following SQL commands built-in:

UPDATE, VALUES, INSERT, ORDER, SELECT, WHERE, DELETE, SET, and JOIN.

All the Commands above are implemented in my_sqlite_request.py within the MySqliteRequest class.
The My-sqlite CLI is implemented in my_sqlite_cli.py within the CLI class.

Altogether serves the purpose to query, update, delete, and in general manipulate csv files that function as databases.

## Technologies

This project was built using:

* Python 3.9.9
* pandas >= 1.2.4
* pytest >= 6.2.5

## Setup

- To install all the libraries and setup the python3 env:

    - ```$>make```

- To test my_sqlite_request.py, edit the ```/my-sqlite/test/qwasar_tests.py``` main function and run:
     - ```make test```
    - ```make reset_db```

- To run the CLI use this make command (example cli inputs can be found in ```/my-sqlite/test/qwasar_tests.py```):

    - ```$>make cli```

- If you would like to revert any change to the csv files:

    - ```$>make reset_db```

## Prerequisites

Please make sure you have Python3 and pip installed on your computer.

# Project Title

Course project for MongoDB for Python developers on a movie browsing catalogue (mflix).

This software project is part of the [course](https://university.mongodb.com/courses/M220P/about) provided by MongoDB University.

## Summary

  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the tests](#running-the-tests)
  - [License](#license)

### Prerequisites

You will need a MongoDB cloud account to access the sample database stored in the Atlas cluster.
Get the Atlas SRV connection string like shown below, for the driver to connect to.

    mongodb+srv://<username>:<password>@<cluster>/<dbname>


### Installation

Open the file [dotini_unix](dotini_unix) and replace the Atlas SRV connection string with yours. Also change your secret key and
rename it as a .ini file.

    mv dotini_unix .ini

Now, create a virtual environment and install the dependencies for the project.

    pip install -r requirements.txt

Run the application.

    python run.py

## Running the tests

To run individual unit tests, follow with their unit test name.

    pytest -m UNIT_TEST_NAME

For example to check connection:

    pytest -m connection

## License

This project is part of a free course provided by [MongoDB University](https://university.mongodb.com/). Copyright terms can be found under [MongoDB website](https://www.mongodb.com/legal/terms-of-use)



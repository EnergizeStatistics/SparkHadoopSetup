# Spark Installation Script #
This shell script installs the `Spark` framework on `Ubuntu`, configures the `PySpark` (using `Python 3`) and `SparkR` APIs, installs `Jupyter Notebook`, enables Jupyter to work with `R`, and finally installs `Hadoop`.

## Description ##
I found various instructions when installing the abovementioned software. Some instructions are obsolete; some miss steps (to me). I guess the latter is because the author's machine already have the dependencies or the required system settings that I do not. These are my steps after a clean installation of Ubuntu 17.10, which comes with Python 3.6. At the time of this writing, the most recent version of Spark is 2.2.0 and that for Hadoop is 2.7.4. 

## Requirements ##
Ubuntu.

## Usage ##
Run the script line by line as user interaction is required. Also some commented steps are not shell commands 
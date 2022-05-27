## 1. Introduction

Python 3.8 image with pyodbc == 4.0.30 and JRE

## 2. Requirements

1. [Docker](https://docs.docker.com/get-docker/)

## 3. Docker pull

You can download the full image from [Docker Hub](https://hub.docker.com/) with the following command.

````
docker pull davma/python-pyodbc-jre
````

## 4. Image build

You can run the image build with the following commands

````
git clone https://github.com/davma-io-images/python-pyodbc-java.git
cd python-pyodbc-java
docker build -t python-pyodbc-jre .
````

## 5.Documentation and guides

[Microsoft ODBC 17](https://docs.microsoft.com/en-us/sql/connect/odbc/linux-mac/installing-the-microsoft-odbc-driver-for-sql-server?view=sql-server-2017)

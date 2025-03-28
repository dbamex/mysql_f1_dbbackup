# My SQL DB F1 Backup 


This is a backup to create a sample database for F1 data, this comprehends data from 1950 up to last race of 2024. 

Data is provided as is , this is just an example to query mysql databases and there's no guarantee about the data itself, it should be only used to test SQL commands. 

## Usage

1. Clone the repository locally 
2. If not exists create database
    1. mysql -u root -p -e "create database f1"
3. Import the database:
    1. mysql -u root -p f1 < yourlocalfile.sql
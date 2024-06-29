# RestAPI-to-Spreadsheet

### This project creates an Excel spreadsheet populated with items from a Rest API database.

Note: A '.env' file must be created in the same directory with the variables "API_SID" and "API_TOKEN" for it to funciton.

DEPENDENCIES:

+ openpyxl \- to generate and populate a spreadsheet
+ requests \- to talk to the CSSI API
+ hashlib \- to generate an md5 hash for the API key
+ os \- to enable use of enviroment variables
+ python-dotenv \- to load environment variables in using .env file

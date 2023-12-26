# Sentra Enterprise_Rest_API_Newman

  

## How to run this project

- Clone this project

- Open with Postman / Command Shell

- Run Command:

```console

newman run Sentra_Enterprise.postman_collection.json -e Sentra_Enterprise.postman_environment.json

```

- Run Command for Report:

```console

newman run Sentra_Enterprise.postman_collection.json -e Sentra_Enterprise.postman_environment.json -r cli,htmlextra

```

  

## Technology used:

- postman 

- Newman

  

## Prerequisite:

- Jdk

- Node Js

- Newman

- Html Report Library

  

## Newman and Report Installation Process:

- Newman Install Command:

```console

npm install -g newman-reporter-htmlextra

```

- Newman Html Report Install Command:

```console

npm install -g newman-reporter-htmlextra

```

  

## API Documentation:

http://13.58.91.85/

  

## Test case list:

1.  ### Admin Login

> Create Data Sets Using the documented criteria and validate

1. > Response Status Code

2. > Response Object property

3. > Full name 

4. > Message 



  

2. ### Add User

> In the test case you need to validate the following field values.Used Dynamic random value

1. > Status code

2. > Full Name 

3. > CompanyUserID

4. > Email

5. > Phone code

 4. > Phone no

 6. > Designation

7.  ### View User

> In the test case you need to validate the following field values:

1. > Only Message

4.  ### Verify Verify Updated Student Details

> In the test case you need to validate the following field values:

1.  > Status code

2. > Content-Type

3. > Message

4. > Designations

8.  ### Delete Specific User

> In the test case you need to validate the following field values:

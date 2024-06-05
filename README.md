# Student-Details-API-Testing
This project demonstrates API testing using Postman, providing a collection of tests to validate various API endpoints. 

### **Features**

- Tests for GET, POST requests
- Collection of tests covering different API endpoints
- Environment setup for easy switching between environments
- Pre-request scripts for data setup
- Test scripts for assertions and validations

## API Documentation:
-https://documenter.getpostman.com/view/34981174/2sA3QzZ8Z5
  
### **Technology used:**
- Postman
- Newman

### **Prerequisite:**
- Node Js
- Newman
- Newman Html Report Library

### **Installation**

1. Postman: If you haven't already, [download and install Postman.](https://www.postman.com/downloads/)
2. Clone the repository:
 ```console 
  git clone https://github.com/farihahoque/Student-Details-API-Testing.git
```
3. Import the Postman collection:
    - Open Postman.
    - Click on the Import button.
    - Select the file from the repository.
4. Import the Postman environment:
    - In Postman, click on the gear icon in the top right corner.
    - Select **Import** and choose the file.
5. Newman and Report Installation Process:
    - Newman Install Command:
     ```console 
      npm install -g newman
    ```
    - Newman Html Report Install Command:
     ```console 
      npm install -g newman-reporter-htmlextra
    ```
### **Usage**
1. Select Environment:
    -   In Postman, select the appropriate environment (e.g., Development, Production) from the top-right dropdown.
3. Run Collection:
    -   Select the imported collection from the Collections sidebar.
    -   Click on the Runner button to open the collection runner.
    -   Select the desired environment.
    -   Click Start Test to run the collection.
8. View Results:
    -   Once the tests are complete, view the results in the Runner tab.
    -   Detailed test results can be viewed for each request.

## **Testing**

## Test Case Scenarios:

## _**1. Get Student Details**_

### Request URL: https://thetestingworldapi.com/api/studentsDetails
### Request Method: GET
### Request Body:None

  **Response Body:**
 ```console 
[
    {
        "id": 10287875,
        "first_name": "Medha",
        "middle_name": "P",
        "last_name": "Singh",
        "date_of_birth": "15/10/1900"
    },
    {
        "id": 10287873,
        "first_name": "kanaga",
        "middle_name": "Gopal",
        "last_name": "Muthu",
        "date_of_birth": "20/09/1989"
    },
    {
        "id": 10287872,
        "first_name": "Testing",
        "middle_name": "B",
        "last_name": "Hello",
        "date_of_birth": "01/01/1998"
    },
    {
        "id": 10287871,
        "first_name": "Testing",
        "middle_name": "B",
        "last_name": "Hello",
        "date_of_birth": "01/01/1998"
    },
    {
        "id": 10287870,
        "first_name": "Testing",
        "middle_name": "B",
        "last_name": "Hello",
        "date_of_birth": "01/01/1998"
    },
    {
        "id": 10287869,
        "first_name": "Testing",
        "middle_name": "B",
        "last_name": "Hello",
        "date_of_birth": "01/01/1998"
    },
    {
        "id": 10287868,
        "first_name": "Testing",
        "middle_name": "B",
        "last_name": "Hello",
        "date_of_birth": "01/01/1998"
    },
    {
        "id": 10287867,
        "first_name": null,
        "middle_name": null,
        "last_name": null,
        "date_of_birth": null
    },
    {
        "id": 10287866,
        "first_name": "Testing 2",
        "middle_name": "lien 2",
        "last_name": "Auto 2",
        "date_of_birth": "sample string 5"
    },
    {
        "id": 10287863,
        "first_name": "Antonio",
        "middle_name": "Rose",
        "last_name": "Chiquito",
        "date_of_birth": "23/02/1998"
    },
    {
        "id": 10287861,
        "first_name": "Emmanuel",
        "middle_name": "Rose",
        "last_name": "Chiquito",
        "date_of_birth": "23/02/1998"
    },
    {
        "id": 10287860,
        "first_name": "Emmanuel",
        "middle_name": "Rose",
        "last_name": "Chiquito",
        "date_of_birth": "23/02/1998"
    },
    {
        "id": 10287859,
        "first_name": "Arizbeth",
        "middle_name": "Rose",
        "last_name": "Garnica",
        "date_of_birth": "13/11/1998"
    },
    {
        "id": 10287858,
        "first_name": "Furkan",
        "middle_name": "A",
        "last_name": "Simsek",
        "date_of_birth": "07/02/1996"
    },
    {
        "id": 10287857,
        "first_name": "Raul",
        "middle_name": "sample string 3",
        "last_name": "sample string 4",
        "date_of_birth": "sample string 5"
    },
    {
        "id": 10287856,
        "first_name": "sample string 2",
        "middle_name": "sample string 3",
        "last_name": "sample string 4",
        "date_of_birth": "sample string 5"
    },
    {
        "id": 10287854,
        "first_name": "sample string 2",
        "middle_name": "sample string 3",
        "last_name": "sample string 4",
        "date_of_birth": "sample string 5"
    },
    {
        "id": 10287853,
        "first_name": "sample string 2",
        "middle_name": "sample string 3",
        "last_name": "sample string 4",
        "date_of_birth": "sample string 5"
    },
    {
        "id": 10287852,
        "first_name": "Salman",
        "middle_name": "",
        "last_name": "Khan",
        "date_of_birth": "14/10/1996"
    },
    {
        "id": 10287851,
        "first_name": "Ajit",
        "middle_name": "Kumar",
        "last_name": "Singh",
        "date_of_birth": "14/02/1997"
    },
    {
        "id": 10287850,
        "first_name": "Salman",
        "middle_name": "",
        "last_name": "Khan",
        "date_of_birth": "14/10/1996"
    },
    {
        "id": 10287849,
        "first_name": "sample string 2",
        "middle_name": "sample string 3",
        "last_name": "sample string 4",
        "date_of_birth": "sample string 5"
    },
    {
        "id": 10287848,
        "first_name": null,
        "middle_name": null,
        "last_name": null,
        "date_of_birth": null
    },
    {
        "id": 10287847,
        "first_name": "Hello",
        "middle_name": "A",
        "last_name": "TestingWorld",
        "date_of_birth": "12/12/1934"
    },
    {
        "id": 10287846,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287845,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287844,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287843,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287842,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287841,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287840,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287839,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287838,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287837,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287836,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287835,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287834,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287833,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287832,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287831,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287830,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287829,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287828,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287827,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287826,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287825,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287824,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287823,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287822,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287821,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287820,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287819,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287818,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287817,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287816,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287815,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287814,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287813,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287812,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287811,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287810,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287809,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287808,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287807,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287806,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287805,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287804,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287803,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287802,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287801,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287800,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287799,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287798,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287797,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287796,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287795,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287794,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287793,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287792,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287791,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287790,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287789,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287788,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287787,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287786,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287785,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287784,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287783,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287782,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287781,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287780,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287779,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287778,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287777,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287776,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287775,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287774,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287773,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287772,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    },
    {
        "id": 10287771,
        "first_name": "MB",
        "middle_name": "Mamun",
        "last_name": "Bhuiyan",
        "date_of_birth": "11-29-1999"
    }
]
```
### Post-Request Script:
```console 
var jsonData = pm.response.json()
var status=pm.response.code
console.log(status)
console.log(jsonData.length)

```
 ## _**2. Create Student Details By ID**_
### Request URL: https://thetestingworldapi.com/api/studentsDetails/id
### Request Method: POST
### Pre-Request Script:
```console 
 var first_name=pm.variables.replaceIn('{{$randomFirstName}}')
pm.environment.set("first_name",first_name)
var middle_name=pm.variables.replaceIn('{{$randomLastName}}')
pm.environment.set("middle_name",middle_name)
var last_name=pm.variables.replaceIn('{{$randomLastName}}')
pm.environment.set("last_name",last_name)

const moment =require('moment')
const today = moment()
var date_of_birth= today.format("YYYY-MM-DD")
pm.environment.set('date_of_birth',date_of_birth)
```
### Request Body:
 ```console 
{ 
"first_name": "{{first_name}}", 
"middle_name": "{{middle_name}}", 
"last_name": "{{last_name}}", 
"date_of_birth": "{{date_of_birth}}" 
}
```
### Response Body:
 ```console 
{
    "id": 10287876,
    "first_name": "Rita",
    "middle_name": "Abernathy",
    "last_name": "Wisozk",
    "date_of_birth": "2024-06-05"
}
```
### Post-Request Script:
```console 
 var status=pm.response.code
console.log(status)
var jsonData=pm.response.json()
pm.environment.set("id",jsonData.id)
pm.test('id validation',function(){
    pm.expect(jsonData.id).to.eql(pm.environment.get('id'))
    pm.response.to.have.status(201);
})
pm.test('first name validation',function(){
    pm.expect(jsonData.first_name).to.eql(pm.environment.get('first_name'))
    pm.response.to.have.status(201);
})
pm.test('middle name validation',function(){
    pm.expect(jsonData.middle_name).to.eql(pm.environment.get('middle_name'))
    pm.response.to.have.status(201);
})
pm.test('last name validation',function(){
    pm.expect(jsonData.last_name).to.eql(pm.environment.get('last_name'))
    pm.response.to.have.status(201);
})
pm.test('date validation',function(){
    pm.expect(jsonData.date_of_birth).to.eql(pm.environment.get('date_of_birth'))
    pm.response.to.have.status(201);
})

```
## _**3.  Get Student Details**_

### Request URL: https://thetestingworldapi.com/api/studentsDetails/id
### Request Method: GET
### Request Body: None

  **Response Body:**
 ```console
{
    "status": "true",
    "data": {
        "id": 10287876,
        "first_name": "Rita",
        "middle_name": "Abernathy",
        "last_name": "Wisozk",
        "date_of_birth": "2024-06-05"
    }
```
### Post-Request Script:
```console 
 var status = pm.response.code;
console.log(status);
var jsonData = pm.response.json();
const schema={
    
    "type": "object",
    "properties": {
        "status": {
            "type": "string"
        },
       
        "data": {
            "type": "object",
            "properties": {
                "id": {
                    "type": "integer"
                },
                "first_name": {
                    "type": "string"
                },
                "middle_name_name": {
                    "type": "string"
                },
                "last_name": {
                    "type": "string"
                },
                "date_of_birth": {
                    "type": "string"
                }},
            "required": ["id", "first_name","middle_name","last_name","date_of_birth"]
}
    },
    "required": ["status", "data"]
}
pm.test('valid response', function () {
    pm.response.to.have.jsonSchema(schema);
});
pm.test("id validation", function () {
    pm.expect(jsonData.data.id).to.eql(pm.environment.get('id'));
});
pm.test("first name validation", function () {
    pm.expect(jsonData.data.first_name).to.eql(pm.environment.get('first_name'));
});
```

 ## _**4. Create Technical Skills**_
### Request URL:https://thetestingworldapi.com/api/technicalskills
### Request Method: POST

  **Request Body:** 
 ```console  { 
"id": 1, 
"language": [ 
"{{lang1}}", 
"{{lang2}}" 
], 
"yearexp": "{{exp}}", 
"lastused": "{{lastused}}", 
"st_id": {{id}}
} 

```
  **Response Body:**
 ```console 
{
    "firstname": "mimma",
    "lastname": "hoque",
    "totalprice": 1167798,
    "depositpaid": true,
    "bookingdates": {
        "checkin": "2013-02-23",
        "checkout": "2014-10-23"
    },
    "additionalneeds": "Breakfast"
}
```
 ## _**5. Create Student Addresses**_
### Request URL: https://thetestingworldapi.com/api/studentsDetails/addresses
### Request Method: POST
### Pre-Request Script:
```console 
 var House_Numb=pm.variables.replaceIn('$randomAlphaNumeric')
pm.environment.set("House_Numb",House_Numb)

var city=pm.variables.replaceIn('$randomCity')
pm.environment.set("city",city)

var state=pm.variables.replaceIn('$randomStreetName')
pm.environment.set("state",state)

var cont=pm.variables.replaceIn('$randomCountry')
pm.environment.set("country",cont)

var std_code=pm.variables.replaceIn('$randomCountryCode')
pm.environment.set("code",std_code)

var hous=pm.variables.replaceIn('$randomAlphaNumeric')
pm.environment.set("house",hous)

var num=pm.variables.replaceIn('$randomPhoneNumber')
pm.environment.set("num",num)

var cont=pm.variables.replaceIn('$randomCountry')
pm.environment.set("country",cont)
```

  **Request Body:** 
 ```console   {
{ 
"Permanent_Address": { 
"House_Number": "{{House_Numb}}",
"City": "{{city}}",
 "State": "{{state}}", 
"Country": "{{country}}",
"PhoneNumber": [ 
{ 
"Std_Code": "{{code}}",
"Home": "{{house}}",
 "Mobile": "{{num}}" 
},
{ 
"Std_Code": "{{code}}",
"Home": "{{house}}", 
"Mobile": "{{num}}" 
} 
] 
},
"stId": {{id}}
} 

```
  **Response Body:**
 ```console
{
    "status": "true",
    "msg": "Add  data success"
}
```
### Post-Request Script:
```console 
var status=pm.response.code
console.log(status)

var jsonData=pm.response.json()
pm.test('status validation',function(){
    pm.expect(jsonData.status).to.eql('true')
;
})

pm.test('msg validation',function(){
    pm.expect(jsonData.msg).to.eql('Add  data success')
;
})
```

 ## _**6. Get Final Student Details_
### Request URL: https://thetestingworldapi.com/api/FinalstudentsDetails/id
### Request Method: GET

  **Response Body:**
 ```console
{
    "status": "true",
    "data": {
        "first_name": "Rita",
        "middle_name": "Abernathy",
        "last_name": "Wisozk",
        "date_of_birth": "2024-06-05",
        "TechnicalDetails": [
            {
                "id": 797362,
                "language": [
                    "French",
                    "English"
                ],
                "yearexp": "10",
                "lastused": "2024-05-31",
                "st_id": "10287876"
            }
        ],
        "Address": [
            {
                "Permanent_Address": {
                    "House_Number": "$randomAlphaNumeric",
                    "City": "$randomCity",
                    "State": "$randomStreetName",
                    "Country": "$randomCountry",
                    "PhoneNumber": [
                        {
                            "Std_Code": "$randomCountryCode",
                            "Home": "$randomAlphaNumeric",
                            "Mobile": "$randomPhoneNumber"
                        },
                        {
                            "Std_Code": "$randomCountryCode",
                            "Home": "$randomAlphaNumeric",
                            "Mobile": "$randomPhoneNumber"
                        }
                    ]
                },
                "Current_Address": null,
                "stId": "10287876"
            }
        ]
    }
}
```

  **Post-Request Script:** 
 ```console
 var status = pm.response.code
console.log(status)
var jsonData = pm.response.json();
pm.test("lang validation", function () {
    pm.expect(jsonData.data.TechnicalDetails[0].language[0]).to.eql(pm.environment.get('lang1'));
});
pm.test("year exp validation", function () {
    
    pm.expect(parseInt(jsonData.data.TechnicalDetails[0].yearexp)).to.eql(pm.environment.get('exp'));
});

pm.test("house numb validation", function () {
 console.log(jsonData.data.Address[0].Permanent_Address.House_Number)
 console.log(pm.environment.get('House_Numb'))
    pm.expect(jsonData.data.Address[0].Permanent_Address.House_Number).to.eql(pm.environment.get('House_Numb'));
});

pm.test("City validation", function () {
    pm.expect(jsonData.data.Address[0].Permanent_Address.City).to.equal(pm.environment.get("city")); 
});

pm.test("Country validation", function () {
    pm.expect(jsonData.data.Address[0].Permanent_Address.Country).to.equal(pm.environment.get("country")); 
});

pm.test("Mobile validation", function () {
    pm.expect(jsonData.data.Address[0].Permanent_Address.PhoneNumber[0].Mobile).to.equal(pm.environment.get("num")); 
});

pm.test("Current Address validation", function () {
    pm.expect(jsonData.data.Address[0].Current_Address).to.equal(null); 
});

```

## Run Command:  
- Run Command for Console: 
```console 
newman run studentdetails.postman_collection.json -e student.postman_environment.json
```
- Run Command for Report: 
```console 
newman run studentdetails.postman_collection.json -e student.postman_environment.json -r cli,htmlextra
```

## Newman Report Summary:
![image](https://github.com/farihahoque/Student-Details-API-Testing/assets/49908132/554300ca-25d6-45f4-b3f0-0393ab9799c2)
![image](https://github.com/farihahoque/Student-Details-API-Testing/assets/49908132/e580e07c-bf3f-433c-845d-d962ca67dbd7)
![image](https://github.com/farihahoque/Student-Details-API-Testing/assets/49908132/85df1b73-d01e-4139-b4d7-1d850a09e8d1)
![image](https://github.com/farihahoque/Student-Details-API-Testing/assets/49908132/728db705-1593-4124-b014-c4810a669531)









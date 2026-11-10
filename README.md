## Postman Employee REST API Testing With Newman Reporting

## About this project
This is employee api automation project.This project is faclated to create employee,update employee,get employee list and search employee with different parameter.
Here we have create automation and generate a newman report.

## Features
- Employee Creation API Testing
- Employee Update API Testing
- Get All Employees API Testing
- Employee Search with Different Parameters
- API Response Validation
- Automated Test Execution with Newman
- HTML Test Report Generation

## Pre-requisites
- Node.js
- Postman
- Visual Studio Code

## Tools and Technologies
- Postman 
- Visual Studio Code 
- Node.js 
- Git and GitHub
  
## API Documentation 
[Employee API Documentation](https://documenter.getpostman.com/view/49956893/2sBYHUUg1H)

## How to run this project
### Clone Project

```bash
git clone https://github.com/rukhsanasultanaritu/EmployeeRESTAPITestingWithNewmanReporting.git
```
## Run the Commands
### Step 1: Initialize npm
```bash
npm init -y
```
### Step 2: Install Newman
```bash
npm i newman
```
### Step 3: Run the Postman Collection
```bash
npx newman run collection.json -e "environment.json"
```
### Step 4: Install HTML Extra Reporter
```bash
npm i newman-reporter-htmlextra
```
### Step 5: Generate the HTML Report
```bash
node .\report.js
```
## Newman HTML Report
The following screenshot shows the Newman HTML test execution report.

<img width="1731" height="1610" alt="image" src="https://github.com/user-attachments/assets/9a894a64-b441-4dca-97f5-02e3216da0a4" />
<img width="1731" height="2384" alt="image" src="https://github.com/user-attachments/assets/4563f3bd-e030-438b-a94e-ac0b7038ec78" />

### Project Links

[GitHub Repository](https://github.com/rukhsanasultanaritu/EmployeeRESTAPITestingWithNewmanReporting.git)

## Bug Reporting
[View Bug Reports in Jira](https://sultanaritu673.atlassian.net/jira/software/projects/ERA/list?jql=project+%3D+ERA+ORDER+BY+cf%5B10019%5D+ASC&atlOrigin=eyJpIjoiMzhjZTFkMGY5M2M2NGNkNDkxNDRjNDY1NmE2NjkxYmIiLCJwIjoiaiJ9)
[Download Bug Report Documentation (Excel)](https://1drv.ms/x/c/f6dd8cfc531102e5/IQDwiJNrINKzSozA-oP-hoFOAR2vTmUTmymF94eNKk4Rk0E?e=x5qP1t)

## Author
Rukhsana Sultana Ritu | CSE Graduate | Aspiring Software QA Engineer






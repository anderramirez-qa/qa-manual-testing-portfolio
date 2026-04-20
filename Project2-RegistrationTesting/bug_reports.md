## Project: GeekRetail Registration Testing

# 🐞 Bug Reports - GeekRetail
Test form: https://testing1.geekqa.net/

---

## 🐞 BG001 - Name field accepts invalid data

### Environment
Windows 10, Google Chrome (Version 147.0.7727.56)

### Priority
High

### Severity
Critical

### Description
System allows invalid data such as numbers or just spaces in the Name field.

### Steps to Reproduce
1. Open Employee Registration form
2. Enter spaces or numbers in the Name field
3. Fill the remaining fields with valid data
4. Click on "submit"

### Expected Result
- Registration should not be completed
- Validation error message should be displayed in the "Name" field indicating the field's requirements

### Actual Result
- System accepts invalid data in the "Name" field
- Employee is registered and added to the table successfully

### Status
Open

---

## 🐞 BG002 - Age field allows values outside the accepted range

### Enviroment
Windows 10, Google Chrome (Version 147.0.7727.56)

### Priority
Medium

### Severity
Medium

### Description
System accepts values outside the established range (18-65) in the Age field

### Steps to Reproduce
1. Open Employee Registration form
2. Enter "5" in the Age field
3. Fill the remaining fields with valid data
4. Click on "submit"

### Expected Result
- System should displayed an error message indicating age should be within the established range
- Employee registration failed

### Actual Result
- System accepts invalid Age data and employee is registered succesfully

### Status
Open

---

## 🐞 BG003 - 

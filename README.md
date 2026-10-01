# Simple Controlled ACL: Restrict Record Access Based on Field Values

## Project Description

This project demonstrates how to use Access Control Lists (ACLs)
in ServiceNow to restrict record access based on field values.

The ACL checks specific field conditions and allows users to access
only the records that satisfy the defined conditions.

## Objective

The main objective of this project is to provide secure and
controlled access to ServiceNow records based on field values.

## Technologies Used

- ServiceNow
- Access Control Lists (ACL)
- JavaScript
- ServiceNow Tables
- Record-Level Security
- Field Conditions
- User Roles

## Main Components

### 1. Access Control List (ACL)

ACL is used to control who can access a record or field
and what operation they can perform.

### 2. Table

The ACL is applied to a ServiceNow table where record access
needs to be controlled.

### 3. Operation

The ACL can control operations such as:

- Read
- Write
- Create
- Delete

### 4. Field Value Condition

The ACL checks the value of a particular field.
Access is allowed only when the defined condition is satisfied.

### 5. User Role

Roles can be used to identify which users are allowed
to access the protected records.

### 6. Condition

The Condition field checks whether the current record
matches the required field value.

### 7. Script

A JavaScript condition can be used when additional
access-control logic is required.

### 8. Target Records

Only records that satisfy the ACL requirements
can be accessed by the user.

## Working Flow

User
   ↓
ServiceNow Record
   ↓
ACL Check
   ↓
User Role Check
   ↓
Field Value Condition
   ↓
Script Check (if required)
   ↓
Access Allowed / Access Denied

## Example

If the field value is:

Department = IT

Then the ACL can be configured to allow access
only when the required condition is satisfied.

## Expected Result

- Authorized users can access the permitted records.
- Users who do not satisfy the ACL conditions cannot access
  the restricted records.
- Record access is controlled based on field values.

## Advantages

- Improves data security
- Provides controlled record access
- Supports role-based security
- Restricts sensitive records
- Reduces unauthorized access

## Conclusion

This project demonstrates how ServiceNow ACLs can be used
to control record access based on field values and user
permissions.

## References

- ServiceNow ACL Documentation
- ServiceNow Access Control Lists
- ServiceNow Security Documentation

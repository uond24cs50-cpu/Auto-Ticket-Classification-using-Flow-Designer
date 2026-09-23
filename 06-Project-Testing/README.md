# Project Testing

## Project Title

Auto Ticket Classification using Flow Designer

## Testing Overview

The Project Testing Phase is performed to verify that the Auto Ticket Classification system works correctly.

The testing validates automatic ticket classification, Category and Subcategory assignment, and email notification.

## Testing Objectives

- Verify automatic ticket classification.
- Verify Category assignment.
- Verify Subcategory assignment.
- Verify email notification.
- Validate ticket information.
- Ensure the flow works correctly for different ticket scenarios.

## Test Case 1 - Wi-Fi Issue

### Test Input

Caller Name: Student

Short Description:

WiFi not working in library

### Expected Result

Category: Network

Subcategory: Wi-Fi

Email notification should be sent to the caller.

### Test Result

The ticket is automatically classified as:

Category: Network

Subcategory: Wi-Fi

The email notification is sent to the caller.

## Test Case 2 - Projector Issue

### Test Input

Caller Name: Student

Short Description:

Projector not turning on

### Expected Result

Category: Hardware

Subcategory: Projector

Email notification should be sent to the caller.

### Test Result

The ticket is automatically classified as:

Category: Hardware

Subcategory: Projector

The email notification is sent to the caller.

## Test Case 3 - Password Issue

### Test Input

Caller Name: Student

Short Description:

Forgot Password

### Expected Result

Category: Access

Subcategory: Forgot Password

Email notification should be sent to the caller.

## Test Case 4 - Slow Computer Issue

### Test Input

Caller Name: Student

Short Description:

Slow Computer

### Expected Result

Category: Performance

Subcategory: Slow Computer

Email notification should be sent to the caller.

## Data Validation

The following data validation checks are performed:

- Mandatory fields are captured correctly.
- Auto-number is generated correctly.
- Category values are stored accurately.
- Subcategory values are stored accurately.
- Reference fields resolve correctly.
- Email notification is generated correctly.

## Email Notification Testing

The email notification is checked after creating a ticket.

The email record can be viewed under:

System Logs → Emails

The email subject and recipient details are verified.

## Testing Result

The testing confirms that the Flow Designer automation correctly classifies IT support tickets based on the Short Description.

The system also sends an email notification to the caller after ticket creation.

## Conclusion

The Project Testing Phase validates the functionality of the Auto Ticket Classification system and confirms that the developed automation works as expected.

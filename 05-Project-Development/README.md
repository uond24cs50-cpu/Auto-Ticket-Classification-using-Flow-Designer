# Project Development

## Project Title

Auto Ticket Classification using Flow Designer

## Development Overview

The Auto Ticket Classification project is developed using ServiceNow Flow Designer.

The system automatically classifies IT support tickets based on the keywords present in the Short Description.

## Technology Used

- ServiceNow
- Flow Designer
- Custom Table
- Choice Fields
- Reference Fields
- Email Notification

## Custom Table Creation

A custom table named Incident Workflow is created to store IT support ticket records.

The table is used to maintain ticket information in a structured format.

## Fields Created

The following fields are created in the Incident Workflow table:

1. Number
2. Caller
3. Category
4. Subcategory
5. Short Description
6. Description
7. State
8. Assigned Group
9. Assigned To

## Category Options

The Category field contains the following choices:

- Network
- Hardware
- Access
- Performance

## Subcategory Options

The Subcategory field contains the following choices:

- Wi-Fi
- Projector
- Forgot Password
- Slow Computer

## Category and Subcategory Mapping

| Category | Subcategory |
|----------|-------------|
| Network | Wi-Fi |
| Hardware | Projector |
| Access | Forgot Password |
| Performance | Slow Computer |

## Dependent Fields

The Subcategory field is configured as a dependent field of the Category field.

This means that the available Subcategory options change according to the selected Category.

## Flow Designer

A Flow Designer flow named:

Auto Classify School IT Tickets

is created for automatic ticket classification.

The flow is triggered when a new Incident Workflow record is created and the Category field is empty.

## Automatic Ticket Classification

The flow checks the Short Description and automatically assigns the appropriate Category and Subcategory.

### Wi-Fi Issue

If the Short Description contains WiFi or Network:

Category: Network

Subcategory: Wi-Fi

### Projector Issue

If the Short Description contains Projector:

Category: Hardware

Subcategory: Projector

### Password Issue

If the Short Description contains Forgot Password:

Category: Access

Subcategory: Forgot Password

### Slow Computer Issue

If the Short Description contains Slow Computer:

Category: Performance

Subcategory: Slow Computer

## Email Notification

After the ticket is classified, an email notification is sent to the caller.

The email confirms that the support request has been submitted.

## Development Result

The project successfully implements automatic ticket classification using ServiceNow Flow Designer.

The system reduces manual effort and provides consistent classification of IT support tickets.

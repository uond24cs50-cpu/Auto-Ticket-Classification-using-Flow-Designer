# Project Documentation

## Project Title

Auto Ticket Classification using Flow Designer

## Project Overview

The Auto Ticket Classification using Flow Designer project is developed to automate the classification of IT support tickets.

The system analyzes the Short Description of a ticket and automatically assigns the appropriate Category and Subcategory.

## Problem Statement

The school IT helpdesk receives multiple incident requests from students and teachers.

Common requests include:

- Wi-Fi issues
- Projector failures
- Password problems
- Slow computers

Currently, IT staff manually review each request and assign a category.

This process is time-consuming and inefficient.

## Project Objective

The main objectives of the project are:

- Automatically classify IT incidents.
- Reduce manual effort for IT staff.
- Improve ticket routing efficiency.
- Provide a no-code and maintainable solution.
- Send an automated email notification to the caller.

## System Components

The project contains the following components:

1. Incident Workflow custom table
2. Category field
3. Subcategory field
4. Short Description field
5. Flow Designer
6. Automatic classification logic
7. Email notification

## Classification Logic

| Keyword / Issue | Category | Subcategory |
|-----------------|----------|-------------|
| WiFi / Network | Network | Wi-Fi |
| Projector | Hardware | Projector |
| Forgot Password | Access | Forgot Password |
| Slow Computer | Performance | Slow Computer |

## Workflow

The system works in the following sequence:

1. A student or teacher creates an IT support ticket.
2. The caller and Short Description are entered.
3. The ticket is created in the Incident Workflow table.
4. Flow Designer is triggered.
5. The Short Description is checked for predefined keywords.
6. The appropriate Category is assigned.
7. The appropriate Subcategory is assigned.
8. An email notification is sent to the caller.

## User Guide

### Step 1

Create a new IT support ticket.

### Step 2

Enter the Caller information.

### Step 3

Enter the issue in the Short Description field.

### Step 4

Submit the ticket.

### Step 5

The Flow Designer automatically identifies the issue.

### Step 6

Category and Subcategory are automatically assigned.

### Step 7

The caller receives an email notification confirming ticket creation.

## Deployment Documentation

The Project Update Set is used to maintain the project configuration.

After completing the project, the Update Set can be changed from In Progress to Complete and exported as an XML file.

## Maintenance

The project uses ServiceNow Flow Designer and no-code configuration.

The classification conditions can be updated when new types of IT support issues need to be included.

## Project Benefits

- Reduces manual ticket classification.
- Improves consistency.
- Saves IT staff time.
- Provides automatic ticket routing.
- Provides email confirmation.
- Easy to maintain and extend.

## Conclusion

The Auto Ticket Classification using Flow Designer project provides an automated solution for classifying school IT support tickets.

The system improves the ticket handling process by automatically assigning Category and Subcategory based on the issue description and sending an email notification to the caller.

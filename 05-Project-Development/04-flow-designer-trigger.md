# Flow Designer Trigger

## Flow Name

Auto Classify School IT Tickets

## Application

Global

## Navigation

1. Open All menus.
2. Search for Flow Designer.
3. Open Flow Designer under Process Automation.
4. Click New.
5. Select Flow.
6. Enter the Flow Name.
7. Set Application to Global.
8. Click Build Flow.

## Trigger Configuration

### Trigger

Record Created

### Table

Incident Workflow

### Condition

Category is Empty

## Purpose

The flow should run when a new Incident Workflow record is created and the Category field is empty.

After the trigger, the flow evaluates the Short Description and automatically classifies the ticket.

## Result

The Flow Designer trigger is configured to start the automatic ticket classification process when a new ticket is created.

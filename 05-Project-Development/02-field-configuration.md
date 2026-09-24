# Field Configuration

## Objective

Create the required fields for the IT ticket table with appropriate data types.

## Required Fields

| Field | Type | Reference / Choice |
|---|---|---|
| Number | Auto Number | - |
| Caller | Reference | sys_user |
| Category | Choice | Network, Hardware, Access, Performance |
| Subcategory | Choice | Wi-Fi, Projector, Forgot Password, Slow Computer |
| Short Description | String | - |
| Description | String | - |
| State | Choice | New, In progress, On hold, Resolved, Closed |
| Assigned Group | Reference | sys_user_group |
| Assigned to | Reference | sys_user |

## Choice Fields

The following fields require choice values:

### Category

- Network
- Hardware
- Access
- Performance

### Subcategory

- Wi-Fi
- Projector
- Forgot Password
- Slow Computer

### State

- New
- In progress
- On hold
- Resolved
- Closed

## Reference Fields

### Caller

Reference table:

sys_user

### Assigned Group

Reference table:

sys_user_group

### Assigned to

Reference table:

sys_user

## Result

All required fields are configured with the appropriate data types, choices, and reference tables.

# Category and Subcategory Dependency

## Objective

Configure a dependency between the Category and Subcategory choice fields.

The available Subcategory values should depend on the selected Category.

## Navigation

1. Open the created table form.
2. Right-click on the Subcategory field.
3. Select Configure Dictionary.
4. Open the Advanced view.
5. Find the Dependent Field section.
6. Enable Use dependent field.
7. Select Category in the Dependent on field.
8. Save the form.

## Dependency Mapping

| Subcategory | Dependent Category |
|---|---|
| Wi-Fi | Network |
| Projector | Hardware |
| Forgot Password | Access |
| Slow Computer | Performance |

## Expected Behaviour

When the user selects a Category, only the corresponding Subcategory should be available.

### Example

If Category is:

Network

The Subcategory should display:

Wi-Fi

If Category is:

Hardware

The Subcategory should display:

Projector.

## Result

The Category and Subcategory fields are configured with dependent choice logic.

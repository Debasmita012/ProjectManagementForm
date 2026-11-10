# Project Management Form

## Description

The Project Management Form is a web-based CRUD application developed using HTML, CSS, Bootstrap, JavaScript, jQuery and JsonPowerDB.

The application stores project details in the `PROJECT-TABLE` relation of the `COLLEGE-DB` database.

### Input Fields

| Field | Description |
|---|---|
| Project-ID | Unique project identifier (Primary Key) |
| Project-Name | Name of the project |
| Assigned-To | Person responsible for the project |
| Assignment-Date | Date of project assignment |
| Deadline | Project completion deadline |

### Features

- **Save:** Inserts a new project record into JsonPowerDB.
- **Update:** Retrieves and modifies an existing project record.
- **Reset:** Clears the form and restores its initial state.
- **Primary Key Validation:** Checks whether a Project ID already exists before enabling data entry.
- **Form Validation:** Prevents submission of empty or invalid fields.
- **Automatic Data Retrieval:** Displays existing project details when an existing ID is entered.

## Technologies Used

- HTML5
- CSS3
- Bootstrap
- JavaScript
- jQuery
- JsonPowerDB
- NetBeans IDE

## Database Configuration

- Database Name: `COLLEGE-DB`
- Relation Name: `PROJECT-TABLE`
- Primary Key: `Project-ID`

## Benefits of Using JsonPowerDB

1. Simple and easy-to-use REST API.
2. Schema-free database structure.
3. High-performance data retrieval.
4. Supports multiple database models.
5. Reduces development time and complexity.
6. Supports serverless application development.
7. Provides real-time database operations.

## Scope of Functionalities

- Create new project records.
- Retrieve project details using Project ID.
- Update existing project information.
- Validate primary key uniqueness.
- Reset form controls.
- Store and retrieve data using JPDB REST APIs.

## Project Status

Completed.

## Release History

### Version 1.0.0
- Created Project Management Form.
- Integrated JsonPowerDB.
- Implemented Save functionality.
- Implemented primary key validation.
- Implemented Update functionality.
- Implemented Reset functionality.
- Added form validation.

## How to Run

1. Clone or download this repository.
2. Open the project in Apache NetBeans.
3. Generate a JsonPowerDB connection token.
4. Configure your connection token locally.
5. Run `index.html` in the browser.

**Note:** Never commit your actual JPDB connection token to a public repository.

## Author

Your Name

## Sources

- https://login2explore.com/jpdb/tutorial.html
- https://login2explore.com/jpdb/docs.html
- https://youtu.be/OS3DFcN9YH8

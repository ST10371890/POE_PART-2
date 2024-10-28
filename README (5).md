# Contract Monthly Claims System (CMCS)

## Project Overview
The Contract Monthly Claims System (CMCS) is a WPF application designed to streamline the claims submission and approval process for lecturers. The system allows lecturers to submit claims, which can be reviewed, approved, or rejected by coordinators.

## Features
- **Lecturer Interface:** Lecturers can submit claims with supporting documentation.
- **Coordinator Dashboard:** Coordinators can view pending claims and approve or reject them.
- **Real-time Status Updates:** Lecturers receive immediate feedback on the status of their claims.
- **Database Integration:** Two databases (`lecturer` and `claims`) are used to manage and store information.

## Database Structure
- **Database Name:** lecturer
  - Stores lecturer information including names, employee numbers, and contact details.
- **Database Name:** claims
  - Stores claim records, including claim IDs, lecturer names, total hours, and claim statuses.

## Implementation Details
The application is structured into several key components:
- **Models:** Define the data structures used within the application.
- **Views:** The user interface elements that allow users to interact with the system.
- **ViewModels:** Facilitate data binding between models and views, ensuring a responsive interface.

## Version Control
The project is managed using Git for version control. Regular commits are made to track changes, and the source code is hosted on GitHub for collaboration and review.

## How to Run the Project
1. Clone the repository from GitHub.
2. Open the solution file in Visual Studio.
3. Ensure that the SQL Server instance is running and the databases are set up as specified.
4. Run the application.

## Feedback Implementation
Feedback from the lecturer has been incorporated into the project to enhance usability, including improved error handling and a more intuitive user interface.

## Contact
For any inquiries or feedback, please contact Mpho Glan Malinga at 078 494 0611 or via email.
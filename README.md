# unknownapp
This is an unknown application written in Java

---- For Submission (you must fill in the information below) ----
### Use Case Diagram
```mermaid
graph TD
User --> LoginStudent
User --> LoginAdmin
User --> Exit

LoginStudent --> CreateProfile
LoginStudent --> ViewCourses
LoginStudent --> EnrollCourse

LoginAdmin --> ManageCourses
LoginAdmin --> ViewStudents
```
### Flowchart of the main workflow

```mermaid
flowchart TD
Start --> Menu
Menu -->|1| StudentLogin
Menu -->|2| AdminLogin
Menu -->|3| Exit

StudentLogin --> CheckStudent
CheckStudent -->|Not Found| CreateProfile
CheckStudent -->|Found| StudentMenu

AdminLogin --> CheckPassword
CheckPassword -->|Wrong| Menu
CheckPassword -->|Correct| AdminMenu
```
### Prompts

- "Explain what this Java enrollment system does"
- "Identify the main functionality of a Java console application"
- "Convert a Java student login system to Python"
- "Create a flowchart for a login menu system"
- "Generate a use case diagram for a course enrollment system"

# Student Records Database

This project contains a MySQL schema for managing student records in a university setting.

## 📦 Tables Included
- `Departments`
- `Instructors`
- `Courses`
- `Students`
- `Enrollments`

## 🔗 Relationships
- One department has many courses
- One instructor teaches many courses
- Students enroll in multiple courses (many-to-many)

## 🚀 How to Run
1. Open MySQL Workbench or CLI
2. Run the `student_records_schema.sql` file
3. The database will be created as `student_records_db`

## 📁 File
- `student_records_schema.sql`: Full schema with constraints and relationships

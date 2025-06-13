 📊 Research Projects Database

This project models a **Research Projects Database** using SQL, including table creation and sample data insertion. It demonstrates relationships between research projects, employees, and funding agencies in an academic or industrial research environment.

---

 🧩 Description

The database stores details about:

- **Projects**: Each project has a unique name (within a funding agency), a manager (who is also an employee), a duration, a budget, and is funded by one agency.
- **Employees**: Employees have unique SSNs and can work on multiple projects. An employee can also manage a project.
- **Funding Agencies**: Each funding agency funds multiple projects and has a unique ID, name, and address.


📝 Sample Data
The script includes sample data inserts for testing:

Employees: John Doe, Jane Smith, Alice Brown

Agencies: Tech Research Fund, Innovation Grants Inc., Global Funding Group

Projects: AI Research, Cloud Migration, Blockchain Platform

Each project is managed and worked on by one of the employees.




✅ Usage
This project is useful for:

Understanding database design and normalization

Learning SQL table creation and data insertion

Demonstrating many-to-many relationships via junction tables

Practicing foreign key constraints and relational modeling





📂 Files Included
SQL schema creation for all tables

Data insertion statements

ER schema design (conceptual)




📌 Notes
Project names are unique within a funding agency (assumption made but not enforced in this schema).

Duration is considered in months for simplicity.

This schema can be further extended to include tasks, milestones, reports, etc.




👨‍💻 Author
Created by Vishwakanth Reddy
Learning SQL, Python, and Web Development at NIAT




🔗 License
This project is open-source and available under the MIT License.

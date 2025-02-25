# Company_Management_Application
Project is simple business application for managing company resources such as projects, departments, teams and employees. The application enables administrators and company users to manage organizational structure and employee information. In the application, users can log in, register, and assign employees to teams, teams to departments, and projects to teams.

The application is designed according to the principles of Clean Architecture, divided into the following layers. Each layer is implemented as a separate project in C# to ensure modularity, scalability, and maintainability.

1. Application Layer
2. Infrastructure Layer
3. Domain Logic Layer
4. Presentation Layer
5. SharedKernel Project

- Login page
![image](https://github.com/user-attachments/assets/8c35d06c-eb98-489d-8580-3dc4c07d48cb)
-Registration page
![image](https://github.com/user-attachments/assets/ed61444e-835b-4dd9-9a34-ef720c83f175)
- Projects Page: Displays a list of projects and their data (team, start date, end date, status and description), allows you to add, delete, edit. The project is assigned to a Team.
![image](https://github.com/user-attachments/assets/3188377a-28c1-458a-8bc7-5078bea32d72)
![image](https://github.com/user-attachments/assets/c7f8e547-1a10-4e9c-9edb-caada692a3f9)
- Departments Page: Displays departments in the company, you can add, delete a new one and edit an existing one.
![image](https://github.com/user-attachments/assets/3be0fe23-0c56-4dc0-a317-c4a78f3353b4)
![image](https://github.com/user-attachments/assets/fa35a736-55d3-47a3-9c31-2b66aca7aed3)
- Teams Page: Displays a list of the teams assigned to the department.You can add, remove, and edit an existing team.
![image](https://github.com/user-attachments/assets/85b8c4ef-cb9d-43b6-88e1-1eb249f1444c)
![image](https://github.com/user-attachments/assets/c3540809-6fb3-4545-b898-9c63dd5b6e47)
- Employees Page: Displays a list of employees and their data, allows you to add, delete, edit an employee. An employee is assigned to a Team.
![image](https://github.com/user-attachments/assets/d83bdc4d-a619-41b5-bb4c-87f4ccaf3958)
![image](https://github.com/user-attachments/assets/c275d80c-3ddc-437e-9f5c-f9a60f1dd2dc)
- Profile Page
![image](https://github.com/user-attachments/assets/ca5bb363-f8e0-41f8-9f8c-05b119c9a7fe)
- Administration Page for Admin: Contains users, admin can edit roles or delete a user.
![image](https://github.com/user-attachments/assets/05e5fe27-4d08-44d2-9b20-8f1abebeec70)
![image](https://github.com/user-attachments/assets/80440377-c66a-4bd8-be06-1fc73c24b29a)




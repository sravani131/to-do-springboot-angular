# to-do-springboot-angular

Todo List
A small full-stack project in Spring Boot and Angular 9.


Design and implement a simple API for Todo itens (CRUD)
Implement security with JWT
Front-end in Angular
Connect both projects
Installing
Clone or download the repository:

$ git clone https://github.com/sravani131/todolist-angular-springboot.git
Running
1 - Open two tabs in the Terminal: 1.1 - Run the service in the first tab:

Navigate to to-dolist-angular-springboot/backend/objectivesss-service/
Run: mvn clean install
1.2 - Run the Angular application in the second tab:

Navigate to to-dolist-angular-springboot/frontend/objectivesss/
Run: ng serve
2 - Open a browser:

http://localhost:4200

Built With
Spring boot
Project Lombok
Swagger
Angular
JWT
Maven

Abstract Design
1 - Application Service layer (serves the requests)

Todos service
2 - Data Storage layer

Stores all todos
3 - Front-end

Allows user interaction with the application

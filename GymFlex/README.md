# GymFlex
Gym Membership and Attendance Tracker - college-level Spring Boot + Maven + MySQL project.

## Run in IntelliJ
1. Extract ZIP and open `GymFlex` in IntelliJ IDEA.
2. Set Project SDK to Java 21.
3. Create MySQL database: `CREATE DATABASE gymflex;`
4. In `src/main/resources/application.properties`, change `spring.datasource.password=root` to your MySQL password.
5. Run `GymFlexApplication.java`.
6. Open http://localhost:8080

Features: member registration, monthly/quarterly/yearly plans, renewal, daily check-in, expired membership rejection, 7-day expiry list, monthly attendance, dashboard, and REST APIs.

# DailyPlanner: Java Activity Planning Application.

Project was upated to JDK 11. AdoptOpenJDK 11.0.11 was used for testing this project. Please make sure that you're using the same JDK to run this project.


Maven 3.8.4 was used for the latest build.

## Setup:

1) Update database credentials in hibernate.cgf.xml to point to your local Postgres database.
2) Run the SQL queries in `public/sql/init.sql` to initialize the tables used by the application.
3) Navigate to the project folder and run `mvn package` in your terminal.
4) Run the project using the following command: `mvn exec:java -Dexec.mainClass=Main`.

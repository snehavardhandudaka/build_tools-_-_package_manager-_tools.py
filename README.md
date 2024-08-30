# build_tools-_-_package_manager-_tools.py

Exercises for Module "Build Tools and Package Manager"

Use repository: https://gitlab.com/twn-devops-bootcamp/latest/04-build-tools/build-tools-exercises


Your team wants to build out a small helper library in Java and ask you to take over the project.



EXERCISE 0: Clone project and create own Git repository
To work with the project for the exercises:

Clone the project and
create your own project/git repository from it

EXERCISE 1: Build jar artifact
You want to deploy the artifact to share that library with all team members. So:

try to build the jar file
The Build will fail, because of a compile error in a test, so you can't build the jar.



EXERCISE 2: Run tests
Fix the test, by changing "true" string to true boolean.
Run gradle test to execute only the tests and check the fix.


EXERCISE 3: Clean and build App
You fixed the test. Now:

clean the build folder with gradle clean and
try to build jar file again.


EXERCISE 4: Start application
Start the jar file to test that the application runs successfully as a jar file

Start app with /build/libs java -jar app-1.0.jar
NOTE: replace "app-1.0.jar" with the name of YOUR jar file.



EXERCISE 5: Start App with 2 Parameters
Now you want to add parameters to your application, so you and other users can pass different values on startup.

Add parameter input to the Java code (see code snippet below, which you can copy)
Rebuild the jar file
Execute the jar file again with 2 params

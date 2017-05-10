I have completed the objective 1 & 2 as requested. Due to time limit, I didn't made any changes other than the requested ones. In reality there are many optimisations and further functionalities can be included.

The existing code has a very simplistic architecture. It has essentially separated all features and actions from one another thus giving way to a loosely coupled code

Suggestions :

1. Found lots of unwanted references in class files. I would remove all unwanted references in order to make the project with out any warnings or messages. It is also a good practice to maintain clean code.

2. There are several security improvements that can be made to the login and authentication methods.

3. Authorization is not checked properly, allows any seller accept/reject offers on other sellers listing. I would improve authorization accross the solution.

4. We can improve a lot on error handling.

5. Lack of base classes. Can implement base classes where ever possible.

6. Can restructure the current solution by extracting different layers into seperate assemblies, so that they are loosely coupled and re-used in effective manner.

7. Lack of logging will lead monitoring the application to difficulties.

8. We can use email notifications in this application very effectively.

9. We should make use of SSL for better security.

10. More changes can be done but due to time constraint, I was not able to list down all.
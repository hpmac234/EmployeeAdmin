README:

1) I developed this web application using ASP.NET core MVC core using visual studio 2019. You could please load the solution file in visual studio and click "IIS Express" from the second button row to run it.

2) Upon application running, it shows a list of different types of employees, 10 hourly, 10 salaried and 10 managers

3) On each line of the list, there're multiple buttons with their functionality self explanatary as below-

1. Work: When you click the button, a new screen comes up, it allows you to put in total work days, when SAVE button is pressed, it does field value validations, and makes calcuations for Accumulated vacation days automatically based on Work() functionality specified in coding test. For validation error, it displays error below the work day field, otherwise it saves the accumulatedVacationDays value to the list, and return to list screen with the updated value

2. Take vacations: It works similar to Work button, implements the TakeVacation() functionality, including field validation, screen update reflecting the changed accumulated value.

3. There're other buttons on the list page, clicking them will display a new Web UI page that provides CRUD functionalities of adding new record to the list, selecting one record from the list, editting and deleting it.



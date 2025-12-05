# CinePlusFalcon-
The CinePlus project is a functional prototype of a point-of-sale system for a movie theater. The project was developed using the Python programming language, the wxGlade extension (and therefore the wx library), and Visual Studio Code with the Pylint extension.

The project contains 4 windows, which handle all the system’s functionality:

-Window 1 (Login):
This is the first window of the project. It grants or denies access to the rest of the software, as a username and password must be entered. The values are obtained through text fields and compared with predefined credentials.

-Window 2 (Ticket Booth):
In this window, the user selects the movie, schedule, theater room, and the number of tickets for two types: adults and children. Through a function linked to the combo box containing the movie list, the system automatically assigns a room and available schedules. The number of ticket types is entered through text fields, and a button is pressed to calculate the price. The resulting information is stored in variables that are passed to the next window. This window also provides options to clear the values or return to the previous window.

-Window 3 (Concessions):
In this window, the user selects the quantity of predefined combos (basic, cuates, family), as well as individual products: popcorn (small, medium, large), soft drinks (sizes and flavors), and candy. A button is pressed to calculate the total price. The window includes options to clear the values and return to the previous window.

-Window 4 (Ticket):
This is the final window of the program. It displays the number of tickets, combos, and individual products selected. This is where the purchase is finalized and payment takes place. All stored variables are displayed here.

To run the program, Visual Studio Code must be installed, along with the wx library and the folder containing the project. To open the program, navigate to:

1. File
2. Open Folder
3. "Locate the folder where the file is stored"
4. Select Folder.
   
Then select the sesionF.py file and run it. You can use Ctrl + F5, or install a Code Runner extension and press the corresponding button to execute (usually located in the upper-right corner).

The project was created by the following students:
-Roberto Aguilar   Developer
-Dulce Adriana Alarcón   Tester
-Alexa Ixchel Calzada   UI/UX
-Daiana Scarlett Javier   Documenter
-Leonel Martínez   Product Owner
-Héctor Uriel Mora   Scrum Master

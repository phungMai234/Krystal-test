# Krystal-test

### Requirement

Link requirement: https://drive.google.com/file/d/19DKU1lr-iODbZWIqptE9Ln9Ymu_sOcX5/view

### My solution

-   First, I read a file selected by the user to get m, n, matrix, and initial position of the robot, list commands.
-   I create a record of the total amount of gold the robot has passed and 2 variables that store the robot's current position.
-   For each command, I will check if the robot is moved to the new location.
    -   If possible, update total, update the new position of the robot, and assign to the matrix at the new position data equal to 0.
    -   Otherwise stop the for loop and return 0.
-   Returns the results by writing the returned output file.

### Run

-   Clone project
    ```
    https://github.com/phungMai234/Krystal-test.git && cd Krystal-test
    ```
-   Or just download index.html
-   Copy path index.html and paste to browser
-   Click select valid file txt and result will be show

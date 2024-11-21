# Ex03 Time Table
# Date:
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using <table> tag in html.

## STEP 4
Add header row using <th> tag.

## STEP 5
Add your timetable using <td> tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="Timetable.css">
        <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
    </head>
    <body>
        <div class="text-center">
            <h1 class="h1">Saveetha Engineering College</h1>

        </div>
        <div>
            <h1 class="h1">Slot Time Table-24005998</h1>
            <table border="2" cellpadding="10">
                <tr>
                    <th>Time</th>
                    <th>Monday</th>
                    <th>Tuesday</th>
                    <th>Wednesday</th>
                    <th>Thursdays</th>
                    <th>Friday</th>
                    <th>Saturday</th>
                </tr>
                <tr>
                    <th>8-10</th>
                    <td>Free slot</td>
                    <td>Comm English</td>
                    <td>Free slot</td>
                    <td>Quantum Physics</td>
                    <td>Comm English</td>
                    <td>Free slot</td>
                </tr>
                <tr>
                    <th>10-12</th>
                    <td>BEEE</td>
                    <td>BEEE</td>
                    <td>Prototyping of IOT</td>
                    <td>Fundamentals Of C</td>
                    <td>Web Application</td>
                    <td>Web Application</td>
                </tr>
                <tr>
                    <th>12-1</th>
                    <td colspan="6" align="center">Lunch Break</td>
                </tr>
                <tr>
                    <th>1-3</th>
                    <td>Web Application</td>
                    <td>Fundamentals Of C</td>
                    <td>Mentor Meet</td>
                    <td>Digital Electronics</td>
                    <td>Quantum Physics</td>
                    <td>Prototyping Of IOT</td>
                </tr>
                <tr>
                    <th>3-5</th>
                    <td>Free slot</td>
                    <td>Digital Electronics</td>
                    <td colspan="4" align="center">Free Slot</td>
                </tr>
            </table>
            <table border="2" cellpadding="10">
                <tr>
                    <th>S.No</th>
                    <th>Subject Code</th>
                    <th>Subject Name</th>
                </tr>
                <tr>
                    <th>1</th>
                    <td>19AI414</td>
                    <td>Fundamentals Of Web Application</td>
                </tr>
                <tr>
                    <th>2</th>
                    <td>19EE404</td>
                    <td>Digital Electronics</td>
                </tr>
                <tr>
                    <th>3</th>
                    <td>19CS420</td>
                    <td>Prototyping Of IOT</td>
                </tr>
                <tr>
                    <th>4</th>
                    <td>SH3214</td>
                    <td>Quantum Physics</td>
                </tr>
                <tr>
                    <th>5</th>
                    <td>19AI304</td>
                    <td>Fundamentals Of C</td>
                </tr>
                <tr>
                    <th>6</th>
                    <td>19EN101</td>
                    <td>Communicative English</td>
                </tr>
                <tr>
                    <th>7</th>
                    <td>19EE305</td>
                    <td>BEEE

                    </td>
                </tr>
 
            </table>
        </div>
    </body>
</html>
css file

/* General Styling */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f9;
    color: #333;
}

/* Header Styling */
h1 {
    font-size: 2.5rem;
    margin: 20px 0;
    color: #444;
}

.text-center h1 {
    font-family: 'Georgia', serif;
    color: #2d89ef;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
}

/* Table Styling */
table {
    width: 90%;
    margin: 20px auto;
    border-collapse: collapse;
    background-color: #fff;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

table th, table td {
    text-align: center;
    padding: 15px;
    border: 2px solid #ddd;
}

table th {
    background-color: #2d89ef;
    color: white;
    font-weight: bold;
}

table td {
    font-size: 1rem;
}

table tr:nth-child(even) {
    background-color: #f9f9f9;
}

table tr:hover {
    background-color: #e3f2fd;
}

/* Special Row Styling */
table td[colspan="6"], table td[colspan="4"] {
    background-color: #ffecb3;
    font-weight: bold;
    font-style: italic;
    color: #555;
}


# OUTPUT

![image](https://github.com/user-attachments/assets/fe5e8a74-9d51-4f97-8cf7-f55838cb984f)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

# time-table
4Design your course timetable and display it in tabular format.
CODE
     <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Timetable</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        th, td {
            border: 1px solid #000;
            padding: 10px;
            text-align: center;
        }

        th {
            background-color: #f2f2f2;
        }

        .recess {
            background-color: #ffeeba;
            font-weight: bold;
        }

        .day {
            background-color: #d9edf7;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <h1>Semester 3 Timetable</h1>
    <table>
        <thead>
            <tr>
                <th>Day/Time</th>
                <th>08:45 - 09:45</th>
                <th>09:45 - 10:45</th>
                <th>10:45 - 11:45</th>
                <th>11:45 - 12:45</th>
                <th>12:45 - 01:15</th>
                <th>01:15 - 02:15</th>
                <th>02:15 - 03:15</th>
                <th>03:15 - 04:15</th>
                <th>04:15 - 05:15</th>
            </tr>
        </thead>
        <body>
            <tr>
                <td class="day">Monday</td>
                <td>Differential Equations<br>Dr. Virendra Kumar</td>
                <td>Data Structures<br>Dr. Rahul Solanki</td>
                <td>Operating Systems<br>Ms. Ashima Jain</td>
                <td class="recess">RECESS</td>
                <td>Data Structures<br>Dr. Rahul Solanki</td>
                <td>Sustainable Eco-Tourism and Entrepreneurship<br>Dr. Anjali Gupta</td>
                <td>Sustainable Eco-Tourism and Entrepreneurship<br>Dr. Anjali Gupta</td>
                <td>AEC - EVS<br>Dr. Devendra Kumar</td>
            </tr>
            <tr>
                <td class="day">Tuesday</td>
                <td>Data Structures<br>Dr. Rahul Solanki</td>
                <td>Operating Systems<br>Ms. Ashima Jain</td>
                <td>Web Design and Development<br>Ms. Ashima Jain</td>
                <td>Web Design and Development<br>Ms. Ashima Jain</td>
                <td class="recess">RECESS</td>
                <td>Operating Systems<br>Ms. Ashima Jain</td>
                <td><br></td>
                <td>AEC - EVS<br>Dr. Devendra Kumar</td>
                <td>AEC - EVS<br>Dr. Devendra Kumar</td>
                
            </tr>
            <tr>
                <td class="day">Wednesday</td>
                <td><br></td>
                <td><br></td>
                <td>Web Design and Development<br>Ms. Ashima Jain</td>
                <td>Web Design and Development<br>Ms. Ashima Jain</td>
                <td class="recess">RECESS</td>
                <td>Differential Equations<br>Dr. Virendra Kumar</td>
                <td>Differential Equations<br>Dr. Virendra Kumar</td>
                <td>vac--yoga practice and philosophy<br>ms anumita</td>
                <td><br></td>
            </tr>
            <tr>
                <td class="day">Thursday</td>
                <td>Data Structures<br>Dr. Rahul Solanki</td>
                <td><br></td>
                <td>Data Structures<br>Dr. Rahul Solanki</td>
                <td>Web Design and Development<br>Ms. Ashima Jain</td>
                <td class="recess">RECESS</td>
                <td>Differential Equations<br>Dr. Virendra Kumar</td>
                <td>Sustainable Eco-Tourism and Entrepreneurship<br>Dr. Anjali Gupta</td>
                <td>Sustainable Eco-Tourism and Entrepreneurship<br>Dr. Anjali Gupta</td>
                <td>Yoga Philosophy and Practice<br>Ms. Anumita Shukla</td>
            </tr>
            <tr>
                <td class="day">Friday</td>
                <td><br></td>
                <td><br></td>
                <td>web development<br>ms ashima jain</td>
                <td>web development<br>ms ashima jain</td>
                <td class="recess">RECESS</td>
                <td>vac -yoga practice and philosophy<br>ms.anumita</td>
                <td>vac -yoga practice and philosophy<br>ms.anumita</td>
                <td><br> </td>
                <td><br></td>
            </tr>
        </tbody>
    </table>
</body>
</html>

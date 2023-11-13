<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title> My Busy Day Schedule</title>
  <style>
    table {
      width: 50%;
      border-collapse: collapse;
      margin-top: 20px;
    }
    th, td {
      border: 1px solid #ddd;
      padding: 8px;
      text-align: center;
      font-family: 'Calibri', sans-serif;
    }
    th {
      background-color: slategray;
      color: white; 
    }
    tr:nth-child(even) {
      background-color: #f9f9f9;
    }
      .important-event {
      background-color: #a0df9e;
      font-weight: bold;
    }
    .early-morning {
      background-color: #708090;
    }
    .sleep-time {
      background-color: #006400; 
      color: white;
    }
    td:first-child {
      width: 25%;
    }
  </style>
</head>
<body>
<table>
  <tr>
    <th>Time</th>
    <th>Event</th>
  </tr>
  <tr class="early-morning">
    <td>8:00 AM</td>
    <td> Breakfast</td>
  </tr>
  <tr>
    <td>9:00 AM</td>
    <td> Optima lessons</td>
  </tr>
<tr>
    <td>11:00 AM</td>
    <td class="important-event"> Mathematics lesson</td>
  </tr>
  <tr>
    <td>1:30 PM</td>
    <td> Lunch</td>
  </tr>
  <tr>
    <td>3:00 PM</td>
    <td class="important-event"> Hudson online lesson</td>
  </tr>
  <tr>
    <td>5:30 PM</td>
    <td> UA-teens study module</td>
  </tr>
  <tr>
    <td>6:00 PM</td>
    <td> Basketball </td>
  </tr>
  <tr>
    <td>8:00 PM</td>
    <td> Dinner</td>
  </tr>
<tr>
    <td>9:00 PM</td>
    <td> Movie Night</td>
  </tr>
  <tr class="sleep-time">
    <td>11:00 PM</td>
    <td> Sleep time</td>
  </tr>
</table>

</body>
</html>

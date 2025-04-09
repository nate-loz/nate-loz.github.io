<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewpoint" content="width=device-width, initial-scale=1.0">
    <title> Gradebook</title>
    <style>
       table {
           width: 100%;
	   boarder-collapse: collapse;
       }
       th, td {
           border: 1px solid #ddd;
           padding: 8px;
           text-align: left;
       }
       th {
           background-color: #f4f4f4;
       }
    </style>
</head>
<body>
    <h1>Gradebook</h1>
    <table id="gradebook">
     <thread>
         <tr>
             <th>Student Name</th>
             <th>Assignment 1</th>
   	     <th>Assignment 2</th>
	     <th>Assignment 3</th>
             <!-- Add more assignment columns as needed -->
         </tr>
     </thread>
     <tbody>
         <!-- Rows will be populated dynamically with JavaScript -->
     </tbody>
    </table>
    <script src="gradebook.js"></script>
</body>
</html>

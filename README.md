<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Form</title>
    <style>
        h1{
            text-align: center;
        }
        body{
            border: 10px solid darkorange;
            margin:10px;
            max-width: 700px;
        }
        input[type=text],[type=radio],[type=checkbox]{
            margin: 20px 0;
            padding:10px;
        }
        select{
            margin:20px 0px;
        }
        .comment{
            width: 300px;
        }
        label{
            margin:5px;
        }
        #comments{
            margin-top: 0px;
            width: 500px;
            height:65px;
        }
    </style>
</head>
<body>
    <main>
  <h1>Students Data Entry Form</h1>
  <label>Student Name:</label> 
  <input type="text"><br>
  <label>Email:</label>
  <input type="Email"><br>
  <label id="gender">Gender:</label>
  <label><input type="radio">Girl</label>
  <label><input type=radio>Boy</label><br>
  <label>Subjects:</label>
  <label><input type="checkbox">Tamil</label>
  <label><input type="checkbox">Telegu</label>
  <label><input type="checkbox">English</label>
  <label><input type="checkbox">Physics</label>
  <label><input type="checkbox">Economics</label><br>
  <label>City / Town:</label>
  <select>
    <option value="Nairobi">Nairobi</option>
    <option value="Mombasa">Mombasa</option>
    <option value="Nakuru">Nakuru</option>
  </select><br>
  <label>Comments:</label><br>
  <div class="comment">
  <input id="comments" type="text"><br>
</div>
  <button type="clear"><a href="#">Clear</a></button>
  <button type="submit"><a href="#">Submit</a></button>
  </main>
</body>
</html># LOG-IN-FORM
A simple log in form

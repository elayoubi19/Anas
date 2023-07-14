<!DOCTYPE html>
<html>
<head>
  <title>Medical Insurance Prediction</title>
</head>
<body>
  <h1>Medical Insurance Prediction</h1>
  
  <form>
    <label for="age">Age:</label>
    <input type="number" id="age" name="age" required><br><br>
    
    <label for="sex">Sex:</label>
    <select id="sex" name="sex" required>
      <option value="male">Male</option>
      <option value="female">Female</option>
    </select><br><br>
    
    <label for="smoker">Smoker:</label>
    <input type="radio" id="smoker_yes" name="smoker" value="yes" required>
    <label for="smoker_yes">Yes</label>
    <input type="radio" id="smoker_no" name="smoker" value="no" required>
    <label for="smoker_no">No</label><br><br>
    
    <label for="children">Number of Children:</label>
    <input type="number" id="children" name="children" required><br><br>
    
    <input type="submit" value="Submit">
  </form>
</body>
</html>

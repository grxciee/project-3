<form method="get" action="process.php"> 
  <fieldset> 
    <legend>Details</legend> 
    <p> 
      <label for="title">Title:</label> 
      <input type="text" id="title" name="title" /> 
    </p> 

    <p> 
      <label for="where">Country:</label> 
      <select id="where" name="where"> 
        <option value="" disabled selected>Choose a country</option> 
        <option value="Canada">Canada</option> 
        <option value="Finland">Finland</option> 
        <option value="United States">United States</option> 
      </select> 
    </p> 
    
    <input type="submit" value="Submit" /> 
  </fieldset> 
</form>


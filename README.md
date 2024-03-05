<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Form with Semantic HTML</title>
  <style>
/* illustration purposes */
body {
  background-color: black;
  color: white;
  font-family: Arial, sans-serif;
  margin: 20px;
}

form {
  max-width: 400px;
  margin: auto;
}

label {
  display: block;
  margin-bottom: 8px;
}

input,
select,
textarea {
  width: 100%;
  padding: 8px;
  margin-bottom: 16px;
}

fieldset {
  border: white solid 1px;
  padding: 20px;
  border-radius: 5px;
}

legend {
  background-color: black;
  color: white;
  padding: 5px 10px;
  border-radius: 5px;
}
  <style>
</head>

<body>
  <h1>Form With Semantic HTML</h1>
  <form>
    <section>
      <label for="fullName">Full Name:</label>
      <input type="text" id="fullName" name="fullName" required>
    </section>
    
    <section>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
    </section>
    
    <section>
      <label for="password">Password:</label>
      <input type="password" id="password" name="password" required>
    </section>
    
    <section>
      <label for="gender">Gender:</label>
      <select id="gender" name="gender">
        <option value="male">Male</option>
        <option value="female">Female</option>
        <option value="other">Other</option>
      </select>
    
    <section>
      <label>
        <input type="checkbox" id="newsletter" name="newsletter">
        Subscribe to Newsletter
      </label>
    </section>
    
    <section>
      <label for="comments">Comments:</label>
      <textarea id="comments" name="comments" rows="4"></textarea>
    </section>

<button type="submit">Submit</button> 
</fieldset>
</form>

</body>
</html>

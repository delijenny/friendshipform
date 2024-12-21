<!DOCTYPE html>
<html lang="en">
<head>
  <title>Tables and Forms</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
</head>
<body>
<section>
<div class="container">
  <h2>Friendship Form</h2>            
  <table class="table table-bordered">
    <thead>
      <tr>
        <th>Name</th>
        <th>Gender</th>
        <th>Contact</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Michael Asante</td>
        <td>Male</td>
        <td>0505758227</td>
      </tr>
      <tr>
        <td>Mary Greatson</td>
        <td>Female</td>
        <td>0257892107</td>
      </tr>
      <tr>
        <td>July Frimpong</td>
        <td>Male</td>
        <td>024466778</td>
      </tr>
      <tr>
        <td>Great Owusuwaa</td>
        <td>Female</td>
        <td>025206780</td>
      </tr>
    </tbody>
  </table>
</div>
</section>
         <section>
<div>
    <form action="action_page">
        <div class="container">
          <h1>Register</h1>
          <p>Please fill this Registraation form.</p>
          <hr>
          <label for="name"><p>Name</p></label>
          <input type="text" placeholder="Enter Full name" name="name" id="name">
          <label for="email"><p>Email</p></label>
          <input type="text" placeholder="Enter Email" name="email" id="email">
          <label for="number"><p>Phone number</p></label>
          <input type="number" Placeholder="Enter Number" name="number" id="number">
          <label for="address"><p>Address</p></label>
          <input placeholder="Enter Address" name="address" id="address">
          <label for="business"><p>Business Category</p></label>
          <input type="radio-button" placeholder="select business category" name="business" id="business">
        </section>
        </hr>
    </form>
</div>
<section>
    <div class="container">
      <h2>List of Friends</h2>            
      <table class="table table-bordered">
        <thead>
          <tr>
            <th>Name</th>
            <th><input type="text"></th>
            <th>Contact</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Email</td>
            <td><input type="text" ></td>
          </tr>
          <tr>
            <td>Contact</td>
            <td><input type="text"></td>
          </tr>
          <tr>
            <td>Gender</td>
            <td><input type="checkbox" id="gender1" name="gender1" value="Male">
              <label for="gender1">Male</label><br>
            <input type="checkbox" id="gender2" name="gender2" value="Female">
            <label for="gender2">Female</label><br> </td>
          </tr>
          <tr>
            <td>Address</td>
            <td><input type="text"></td>
          </tr>
          <tr>
            <td>Business Category</td>
            <td><label for="business" placeholder="select business category">
            <select id="business" name="business list" form="businessform">
              <option value="engineer">Engineer</option>
              <option value="trader">Trader</option>
              <option value="enterpreneur">Enterpreneur</option>
              <option value="other">Other</option>
            </select></td>
          </tr>
        </tbody>
      </table>
    </div>
    </section>
    <button type="submit" class="btn btn-primary">Submit</button>
</body>
</html>



  
      

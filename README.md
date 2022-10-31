# HTML-
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <title>HTML Page</title>
  </head>
  <body>
    <header>
      <h1 style="color: green; text-align: center; font-size: 40px">
        This is my main heading
      </h1>
      <nav>
        <a href="#first-section">Home</a>
        <br />
        <a href="#second-section">About us</a>
        <br />
        <a href="#third-section">Contact us</a>
      </nav>
    </header>

    <table>
      <thead>
        <tr>
          <th>Name</th>
          <th>Gender</th>
          <th>Country</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Abigail</td>
          <td>Female</td>
          <td>Nigeria</td>
        </tr>
        <tr>
          <td>Theresa</td>
          <td>Female</td>
          <td>Nigeria</td>
        </tr>
        <tr>
          <td>John</td>
          <td>Male</td>
          <td>South Africa</td>
        </tr>
      </tbody>
    </table>

    <h4>My favorite meals:</h4>
    <ul>
      <li>Rice</li>
      <li>
        Beans
        <ul>
          <li>White beans</li>
          <li>Porridge beans</li>
        </ul>
      </li>
      <li>Plantain</li>
    </ul>

    <h4>My favorite colors:</h4>
    <ol>
      <li>White</li>
      <li>Black</li>
      <li>Navy blue</li>
    </ol>
  </body>

  <form action="">
    <fieldset>
      <legend>Enter your biodata:</legend>
      <label for="firstName">First Name:</label>
      <input type="text" placeholder="First name" id="firstName" />
      <br />
      <label for="lastName">Last Name:</label>
      <input type="text" placeholder="Last name" id="lastName" /> <br />
      <label for="email">Email Address:</label>
      <input type="email" placeholder="Enter  your email address" id="email" />
      <br />
      <label for="age">Age:</label>
      <input type="number" placeholder="Enter  your age" id="age" />

      <br />
      <label for="fruites">Favorite Fruites:</label>
      <select name="" id="fruites">
        <option value="orange">Orange</option>
        <option value="apple">Apple</option>
        <option value="banana">Banana</option>
      </select>
      <label for="country">Country of Origin:</label>
      <select name="" id="country">
        <option value="" disabled selected>select country</option>
        <optgroup label="Africa">
          <option value="nigeria">Nigeria</option>
          <option value="ghana">Ghana</option>
          <option value="southAfrica">South Africa</option>
        </optgroup>

        <optgroup label="Europe">
          <option value="great-britain">Great Britain</option>
          <option value="spain">Spain</option>
          <option value="germany">Germany</option>
        </optgroup>
      </select>

      <label for="female">Female:</label>
      <input type="radio" name="gender" id="female" />

      <label for="male">Male:</label>
      <input type="radio" name="gender" id="male" />

      <div>
        <input type="checkbox" id="dewey" name="drone" value="dewey">
        <label for="dewey">Dewey</label>
      </div>
  
      <div>
        <input type="checkbox" id="louie" name="drone" value="louie">
        <label for="louie">Louie</label>
        <div>

          <textarea name="" id="" cols="60" rows="10" maxlength="20"> </textarea>
        </div>
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <title>HTML Page</title>
  </head>
  <body>
    <header>
      <h1 style="color: green; text-align: center; font-size: 40px">
        This is my main heading
      </h1>
      <nav>
        <a href="#first-section">Home</a>
        <br />
        <a href="#second-section">About us</a>
        <br />
        <a href="#third-section">Contact us</a>
      </nav>
    </header>

    <table>
      <thead>
        <tr>
          <th>Name</th>
          <th>Gender</th>
          <th>Country</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Abigail</td>
          <td>Female</td>
          <td>Nigeria</td>
        </tr>
        <tr>
          <td>Theresa</td>
          <td>Female</td>
          <td>Nigeria</td>
        </tr>
        <tr>
          <td>John</td>
          <td>Male</td>
          <td>South Africa</td>
        </tr>
      </tbody>
    </table>

    <h4>My favorite meals:</h4>
    <ul>
      <li>Rice</li>
      <li>
        Beans
        <ul>
          <li>White beans</li>
          <li>Porridge beans</li>
        </ul>
      </li>
      <li>Plantain</li>
    </ul>

    <h4>My favorite colors:</h4>
    <ol>
      <li>White</li>
      <li>Black</li>
      <li>Navy blue</li>
    </ol>
  </body>

  <form action="">
    <fieldset>
      <legend>Enter your biodata:</legend>
      <label for="firstName">First Name:</label>
      <input type="text" placeholder="First name" id="firstName" />
      <br />
      <label for="lastName">Last Name:</label>
      <input type="text" placeholder="Last name" id="lastName" /> <br />
      <label for="email">Email Address:</label>
      <input type="email" placeholder="Enter  your email address" id="email" />
      <br />
      <label for="age">Age:</label>
      <input type="number" placeholder="Enter  your age" id="age" />

      <br />
      <label for="fruites">Favorite Fruites:</label>
      <select name="" id="fruites">
        <option value="orange">Orange</option>
        <option value="apple">Apple</option>
        <option value="banana">Banana</option>
      </select>
      <label for="country">Country of Origin:</label>
      <select name="" id="country">
        <option value="" disabled selected>select country</option>
        <optgroup label="Africa">
          <option value="nigeria">Nigeria</option>
          <option value="ghana">Ghana</option>
          <option value="southAfrica">South Africa</option>
        </optgroup>

        <optgroup label="Europe">
          <option value="great-britain">Great Britain</option>
          <option value="spain">Spain</option>
          <option value="germany">Germany</option>
        </optgroup>
      </select>

      <label for="female">Female:</label>
      <input type="radio" name="gender" id="female" />

      <label for="male">Male:</label>
      <input type="radio" name="gender" id="male" />

      <div>
        <input type="checkbox" id="dewey" name="drone" value="dewey">
        <label for="dewey">Dewey</label>
      </div>
  
      <div>
        <input type="checkbox" id="louie" name="drone" value="louie">
        <label for="louie">Louie</label>
        <div>

          <textarea name="" id="" cols="60" rows="10" maxlength="20"> </textarea>
        </div>

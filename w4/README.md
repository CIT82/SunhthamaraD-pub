html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>HTML Elements</title>
    <link rel="stylesheet" href="style.css" />
  </head>

  <body>
    <p>HERO</p>
    <ul>
      <li><data value="398">Hero</data></li>
      <li><data value="399">Villain</data></li>
      <li><data value="400">Mega Weapon</data></li>
    </ul>

    <table>
      <caption>
        He-Man and Skeletor facts
      </caption>
      <tr>
        <td></td>
        <th scope="col" class="heman">He-Man</th>
        <th scope="col" class="skeletor">Skeletor</th>
      </tr>
      <tr>
        <th scope="row">Role</th>
        <td>Hero</td>
        <td>Villain</td>
      </tr>
      <tr>
        <th scope="row">Weapon</th>
        <td>Power Sword</td>
        <td>Havoc Staff</td>
      </tr>
      <tr>
        <th scope="row">Dark secret</th>
        <td>Expert florist</td>
        <td>Cries at romcoms</td>
      </tr>
    </table>
    <label for="pet-select">Choose a pet:</label>

    <select id="pet-select">
      <option value="">--Please choose an option--</option>
      <option value="dog">Dog</option>
      <option value="cat">Cat</option>
      <option value="hamster">Hamster</option>
      <option value="parrot">Parrot</option>
      <option value="spider">Spider</option>
      <option value="goldfish">Goldfish</option>
    </select>
  </body>
</html>

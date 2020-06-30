# forms2
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Register form</title>
  </head>
   <style>
    body
    {
      background-color : yellow;
      color : black;
      font-family : serif;
      font-style : italic;
      font-size : 20px;
    }
    input
    {
      background-color : red;
      opacity : 0.5;
      margin : 20px;
    }
  </style>
  <body>
    <form>
      <table style="text-color:blue">
        <tr>
          <td>
            Name :
          </td>
          <td>
            <input type="text" placeholder="Name" name=" "  required>
          </td>
        </tr>
        <tr>
          <td>
            Password :
          </td>
          <td>
            <input type="Password" placeholder="Password" name=" "  required>
          </td>
        </tr>
      </table>
      <input type="submit">
    </form>
  </body>
</html>

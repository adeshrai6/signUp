
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>Sign Up</title>
  </head>
  <body>
    <div class="container">
      <form id="form" class="form">
        <h2>Register With Us</h2>
        <div class="form-control">
          <label for="username">Username</label>
          <input type="username" id="username" placeholder="Enter username" />
          <small>error message</small>
        </div>
        <div class="form-control">
          <label for="email">Email</label>
          <input type="email" id="email" placeholder="Enter email" />
          <small>error message</small>
        </div>
        <div class="form-control">
          <label for="password">Password</label>
          <input type="password" id="password" placeholder="Enter password" />
          <small>error message</small>
        </div>
        <div class="form-control">
          <label for="password2">Confirm Password</label>
          <input
            type="password"
            id="password2"
            placeholder="Enter password again"
          />
          <small>error message</small>
        </div>
        <button type="submit">Submit</button>
      </form>
    </div>

    <script src="script.js"></script>
  </body>


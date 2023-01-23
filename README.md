# portfolio-website
<!DOCTYPE html>
<html>
<head>
  <title>My Portfolio</title>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
  <header>
    <h1>My Portfolio</h1>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#work">Work</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>
  <section id="about">
    <h2>About Me</h2>
    <p>Sheethal T G, Final year Engineering-2023 ,Tiptur , Karnataka..</p>
  </section>
  <section id="work">
    <h2>My Work</h2>
    <ul>
      <li><a href="#">Project 1</a></li>
      <li><a href="#">Project 2</a></li>
      <li><a href="#">Project 3</a></li>
    </ul>
  </section>
  <section id="contact">
    <h2>Contact Me</h2>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name"><br>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email"><br>
      <label for="message">Message:</label>
      <textarea id="message" name="message"></textarea><br>
      <input type="submit" value="Submit">
    </form>
  </section>
  <script src="script.js"></script>
</body>
</html>

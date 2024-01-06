# Portfolio
# A responsive portfolio page using CSS grids.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: pink;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 1rem;
    }

    main {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    section {
      background-color: #f4f4f4;
      padding: 20px;
      border-radius: 8px;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 1rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Erina Vincent</h1>
    <p>Web Developer</p>
  </header>

  <main>
  <img src = "https://funmauj.b-cdn.net/test/369984.jpg" height = 303px width = 200/>
    <section>
      <h2>Projects</h2>
      <ul>
        <li>Project 1</li>
        <li>Project 2</li>
        <li>Project 3</li>
      </ul>
    </section>

    <section>
      <h2>Skills</h2>
      <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>Database</li>
      </ul>
    </section>

    <section>
      <h2>Contact</h2>
      <p>Email: your.email@example.com</p>
      <p>LinkedIn: linkedin.com/in/yourname</p>
      <p>GitHub: github.com/yourusername</p>
    </section>
  </main>

  <footer>
    &copy; 2024 Your Portfolio. All rights reserved.
  </footer>

</body>
</html>

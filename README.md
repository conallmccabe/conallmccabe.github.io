!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Conall McCabe</title>
  <link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Mono&display=swap" rel="stylesheet">
  <meta name="google-site-verification" content="6mQqQl20dPjvZKLw6y8ewzEPQox2TN-wdZQxKDiMuVU"/>
  <style>
    body {
      margin: 0;
      font-family: 'IBM Plex Mono', monospace;
      background-color: #ffffff;
      color: #000000;
      line-height: 1.6;
      font-size: 16px;
    }

    nav {
      padding: 1rem;
      font-size: 0.95rem;
      border-bottom: 1px solid #ccc;
      position: sticky;
      top: 0;
      background-color: white;
    }

    nav a {
      margin-right: 20px;
      color: black;
      text-decoration: none;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .container {
      max-width: 750px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    h1 {
      font-weight: normal;
      margin-bottom: 0.5rem;
    }

    h2 {
      font-size: 1.1rem;
      margin-top: 3rem;
    }

    img.profile {
      width: 300px;
      border-radius: 5px;
    }
    .small-image {
      width: 300px;
      border-radius: 5px;
      margin-top: 1rem;
    }
    img.teaching, .contact img {
      width: 100%;
      max-width: 500px;
      border-radius: 5px;
      margin-top: 1rem;
    }

    .flex {
      display: flex;
      flex-direction: column;
    }

    .side-by-side {
      display: flex;
      flex-direction: row;
      align-items: flex-start;
      gap: 1.5rem;
      flex-wrap: wrap;
    }

    .side-by-side img {
      flex-shrink: 0;
    }

    .contact {
      margin-top: 2rem;
    }

    .contact img {
      max-width: 180px;
    }

    a {
      color: #0033cc;
    }
    .side-by-side-images {
  display: flex;
  gap: 1rem;
  margin-top: 1rem;
  flex-wrap: wrap;
}

.side-by-side-images img {
  width: 220px;
  border-radius: 5px;
  object-fit: cover;
}
    @media (max-width: 600px) {
      .side-by-side {
        flex-direction: column;
      }
    }
  </style>
</head>

<body>
  <nav>
    <a href="#about">About</a>
    <a href="#publications">Publications</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container">
    <section id="about">
      <h1>Conall McCabe</h1>
      <div class="side-by-side">
        <img src="portrait.jpg" alt="Profile Picture" class="profile" />
        <div>
          <p>I'm a graduate student in Ana Maria Rey's group at JILA and the University of Colorado in Boulder. I'm interested in quantum simulation and metrology using ultracold atoms in optical lattices and tweezers.  </p>
        </div>
      </div>
    </section>

    <section id="publications">
      <h2>Selected Publications</h2>
      <ul>
        <li>C. McCabe, J. Boyd, K. Wang, M. Lebrat, C. Regal, A.M. Kaufman, A.M. Rey, L. Homeier, "Realizing multiorbital Emery models using ultracold atoms" arXiv:2604.22955</li>
      </ul>
    <section id="contact" class="contact">
      <h2>Contact</h2>
      <div class="side-by-side">
        <ul>
          <li>Email: conall.mccabe@colorado.edu</li>
        </ul>
      </div>
    </section>
  </div>
</body>

</html>

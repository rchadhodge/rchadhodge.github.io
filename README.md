<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Blue Pen Consulting LLC</title>
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
    }
    body {
      font-family: 'Roboto', sans-serif;
      color: #000000;
    }
    .background-fixed {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: url('Web background.jpg') no-repeat center center;
      background-size: cover;
      background-attachment: fixed;
      z-index: -1;
    }
    header {
      background-color: rgba(0, 31, 63, 0.9);
      color: #ffffff;
      padding: 1rem;
      text-align: center;
    }
    header img {
      max-width: 300px;
      height: auto;
    }
    nav {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      background: rgba(0, 116, 217, 0.9);
      padding: 0.5rem;
    }
    nav a {
      color: white;
      margin: 0.5rem 1rem;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      background-color: rgba(255, 255, 255, 0.95);
      padding: 2rem;
      margin: 2rem auto;
      border-radius: 8px;
      width: 90%;
      max-width: 1000px;
    }
    footer {
      background-color: rgba(0, 31, 63, 0.9);
      color: white;
      text-align: center;
      padding: 1rem;
    }
    .team, .services, .insights {
      margin-top: 2rem;
    }
    .contact-form label, .contact-form input, .contact-form textarea {
      display: block;
      width: 100%;
      margin-bottom: 1rem;
    }
    .contact-form input, .contact-form textarea {
      padding: 0.5rem;
    }
    .contact-form button {
      background-color: #0074D9;
      color: white;
      padding: 0.7rem 1.5rem;
      border: none;
      cursor: pointer;
    }
    @media (max-width: 600px) {
      nav {
        flex-direction: column;
      }
      section {
        padding: 1rem;
      }
      .contact-form button {
        width: 100%;
      }
      header img {
        max-width: 80%;
      }
    }
  </style>
</head>
<body>
  <div class="background-fixed"></div>
  <header>
    <img src="Logo Final Edit 2.png" alt="Blue Pen Consulting LLC Logo">
  </header>
  <nav>
    <a href="#overview">Overview</a>
    <a href="#services">Services</a>
    <a href="#team">Team</a>
    <a href="#insights">Insights</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="overview">
    <h2>Overview</h2>
    <p>Blue Pen Consulting LLC specializes in helping businesses of all sizes strengthen their contracts and procurement functions. We bring clarity and efficiency through robust procedure development, effective contracting strategies, and hands-on support at every stage of procurement transformation.</p>
  </section>

  <section id="services" class="services">
    <h2>Our Services</h2>
    <ul>
      <li>Procedure Review and Enhancement</li>
      <li>Procedure Development</li>
      <li>Forms and Management Tools</li>
      <li>Strategy Enhancement</li>
      <li>Training</li>
      <li>Drafting, Negotiation, and Management Support</li>
      <li>Project Support</li>
    </ul>
  </section>

  <section id="team" class="team">
    <h2>Our Team</h2>
    <p>Our seasoned procurement and contract staff brings deep industry experience and a pragmatic approach to each engagement. [Add individual bios with photos here if available]</p>
  </section>

  <section id="insights" class="insights">
    <h2>Insights</h2>
    <p>Stay tuned for articles, thought leadership, and updates on trends in procurement and contracting.</p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form class="contact-form" name="contact" method="POST" data-netlify="true">
      <input type="hidden" name="form-name" value="contact">
      <label for="name">Name</label>
      <input type="text" id="name" name="name" required />

      <label for="email">Email</label>
      <input type="email" id="email" name="email" required />

      <label for="message">Message</label>
      <textarea id="message" name="message" rows="5" required></textarea>

      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Blue Pen Consulting LLC. All rights reserved.</p>
  </footer>
</body>
</html>

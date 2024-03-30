    <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="styless.css">
</head>
<body>

  <!-- Navigation -->
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#portfolio">Portfolio</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- Homepage -->
  <section id="home">
    <div class="container">
        <div class="home-image">
            <img src="me.jpg" alt="Your Image">
          </div>
      <h1>Welcome to My Portfolio</h1><br>
      <p> Hello, I'm Prabhleen Kaur, a BTech third-year student with a passion for technology and a strong interest in software development</p>
      <p> As a third-year student, I have gained a deeper understanding of programming concepts, data structures, and algorithms. I am proficient in languages like Java, C, and C++</p>
      <p>As a driven and committed individual, I am passionate about using technology to make a positive impact on society. </p>
    </div>
    
    </div>
  </div>
  </section>

  <!-- About Section -->
  <section id="about">
    <div class="container">
      <h2>About Me</h2><br>
      <p>I am a BTech 3rd year student with a passion for technology and programming. 
        Proficient in Java, C, C++, HTML, CSS, Python, Data Structures and Algorithms (DSA), and SQL, I thrive on solving complex problems and creating innovative solutions. Beyond coding, I find joy in the simple pleasures of life.
        Whether it's diving into a new book to expand my horizons, immersing myself in diverse music genres for inspiration, or embarking on adventures to explore the world's wonders, I embrace each experience with enthusiasm and curiosity.</p>
      <ul>
        <li>Technical Skills: Java,C,C++,Python,DSA,SQL,Linux,Bash,Shell Scripting and many more.</li>
        <li>Interests: Book Reading, Listening Music</li>
      </ul>
    </div>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio">
    <div class="container">
      <h2>Portfolio</h2><br>
      <div class="project">
        <h3>Project - Cafe Management system</h3><br>
        <img src="Top-Book-Cafes-to-explore-in-Delhi-NCR.webp" alt="Project 1"><br>
        <p>Our cafe management system project aims to streamline the operations of a bustling cafe by integrating various functionalities into a centralized platform.
            Leveraging modern technologies such as Java, Spring Boot, and MySQL, the system enables efficient management of customer orders, inventory, employee scheduling, and financial transactions. With an intuitive user interface accessible via web and mobile platforms, cafe staff can easily create, modify, and track orders in real-time, enhancing customer service and satisfaction. 
            Additionally, the system offers comprehensive inventory management capabilities, allowing cafe managers to monitor stock levels, automate reordering processes, and minimize wastage</p><br>
           <h2>Some Exercises of IWT Lab</h2><br>
            <a href="ex1.html">http://127.0.0.1:5500/html/ex1.html</a><br>
            <a href="ex5.html">http://127.0.0.1:5500/html/ex5.html</a><br>
            <a href="ex11.html">http://127.0.0.1:5500/html/ex11.html</a><br>
            <a href="ex10.html">http://127.0.0.1:5500/html/ex10.html</a><br>
            <a href="ex7.html">http://127.0.0.1:5500/html/ex7.html</a><br>

      </div>
      
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <div class="container">
      <h2>Contact Me</h2><br>
      <form id="contact-form">
        <input type="text" placeholder="Name" required>
        <input type="email" placeholder="Email" required>
        <textarea placeholder="Message" required></textarea>
        <button type="submit">Send</button>
      </form>
    </div>
  </section>

  <script>
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function (e) {
        e.preventDefault();

        document.querySelector(this.getAttribute('href')).scrollIntoView({
          behavior: 'smooth'
        });
      });
    });
  </script>

</body>
</html>

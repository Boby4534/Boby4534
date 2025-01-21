<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NextGovtJob - Latest Government Job Updates</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="container">
      <h1>NextGovtJob</h1>
      <p>Your One-Stop Destination for Government Job Updates</p>
    </div>
  </header>
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#jobs">Latest Jobs</a></li>
      <li><a href="#categories">Categories</a></li>
      <li><a href="#contact">Contact Us</a></li>
    </ul>
  </nav>
  <main>
    <section id="jobs" class="container">
      <h2>Latest Government Job Updates</h2>
      <div class="job-card">
        <h3>UPSC Civil Services Exam 2025</h3>
        <p><strong>Last Date to Apply:</strong> 15th March 2025</p>
        <p><strong>Eligibility:</strong> Graduation in any field</p>
        <a href="#">Read More</a>
      </div>
      <div class="job-card">
        <h3>SSC CGL 2025</h3>
        <p><strong>Last Date to Apply:</strong> 10th February 2025</p>
        <p><strong>Eligibility:</strong> Graduation</p>
        <a href="#">Read More</a>
      </div>
    </section>
    <section id="categories" class="container">
      <h2>Job Categories</h2>
      <ul>
        <li>Banking Jobs</li>
        <li>Railway Jobs</li>
        <li>UPSC Jobs</li>
        <li>State Government Jobs</li>
        <li>Teaching Jobs</li>
      </ul>
    </section>
  </main>
  <footer>
    <div class="container">
      <p>&copy; 2025 NextGovtJob. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>/* General Styles */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f9;
}

header {
  background-color: #007bff;
  color: white;
  padding: 20px;
  text-align: center;
}

nav {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px 0;
}

nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav ul li a {
  color: white;
  text-decoration: none;
  font-size: 18px;
}

nav ul li a:hover {
  text-decoration: underline;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px 0;
}

h2 {
  color: #007bff;
}

.job-card {
  background: white;
  margin: 20px 0;
  padding: 15px;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.job-card h3 {
  margin: 0 0 10px;
  color: #007bff;
}

.job-card p {
  margin: 5px 0;
  color: #555;
}

.job-card a {
  color: #007bff;
  text-decoration: none;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
}
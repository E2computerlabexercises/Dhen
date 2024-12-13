<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LAB EXERCISES - ASHLEY DHEN DELA CRUZ</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: white;
            color: maroon;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: maroon;
            color: white;
            text-align: center;
            padding: 1rem;
        }
        nav {
            text-align: center;
            margin: 1rem 0;
        }
        nav a {
            margin: 0 1rem;
            text-decoration: none;
            color: maroon;
            font-weight: bold;
        }
        section {
            margin: 2rem;
        }
        iframe {
            display: block;
            margin: 1rem auto;
            border: 2px solid maroon;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 1rem 0;
        }
        table, th, td {
            border: 1px solid maroon;
        }
        th, td {
            padding: 8px;
            text-align: left;
        }
        form {
            margin: 2rem 0;
        }
        form label {
            display: block;
            margin: 0.5rem 0;
        }
        .form-section {
            margin-bottom: 2rem;
        }
    </style>
</head>
<body>
  <header>
    <h1>LAB EXERCISES</h1>
    <h2>Submitted by: ASHLEY DHEN DELA CRUZ</h2>
    <audio controls>
      <source src="your-audio-file-link.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#blog">Blog</a>
    <a href="#plagiarism">Plagiarism</a>
    <a href="#forms">Forms</a>
  </nav>

  <!-- Home Section -->
  <section id="home">
    <h2>Welcome to My Lab Exercises</h2>
    <p>This website contains all the exercises submitted by Ashley Dhen Dela Cruz.</p>
    <img src="images (4).jpeg" width="600" height="300">

  </section>

  <!-- Blog Section -->
  <section id="blog">
    <h2>The Digital Trinity of Threats: Malware, Spam, and Viruses</h2>
    <p>Online activities are constantly at risk from three main threats: viruses, malware, and spam. Understanding these dangers is the first step in staying safe.</p>
    <h3>Viruses</h3>
    <p>Viruses are harmful programs that attach to files, spread, and can damage your data, slow down your system, or crash it entirely. They often spread through infected email attachments or files from untrusted sources.</p>
    <h3>Malware</h3>
    <p>Malware is any software designed to harm your computer. This includes ransomware (which demands payment to unlock your files), spyware (which tracks your activity), and adware (which displays unwanted ads). Malware is constantly evolving and poses a serious threat.</p>
    <h3>Spam</h3>
    <p>Spam consists of unwanted emails, often containing phishing scams or links to malware. Although it may not directly harm your system, it can lead to identity theft or other security issues.</p>
    <h3>Protection</h3>
    <p>Antivirus software is essential in defending against these threats. It helps by scanning for viruses, blocking harmful websites, and filtering spam. However, it’s also important to stay vigilant, practice safe browsing, and keep your software up to date.</p>
  </section>

  <!-- Plagiarism Section -->
  <!-- Video embedded from YouTube -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lm8R-_CALd4?si=4yAATO9z3CXQqOCD" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  <section id="plagiarism">
    <h2>What Constitutes Plagiarism?</h2>
    <table>
      <thead>
        <tr>
          <th>Type</th>
          <th>Description</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Direct Copying</td>
          <td>Word-for-word reproduction of text without quotation marks and proper citation.</td>
        </tr>
        <tr>
          <td>Paraphrasing without Attribution</td>
          <td>Restating someone else's ideas in your own words without acknowledging the original source.</td>
        </tr>
        <tr>
          <td>Self-Plagiarism</td>
          <td>Submitting the same work for multiple assignments without permission.</td>
        </tr>
        <tr>
          <td>Improper Citation</td>
          <td>Failing to correctly cite sources, even if the work is paraphrased.</td>
        </tr>
        <tr>
          <td>Mosaic Plagiarism</td>
          <td>Interweaving copied phrases with original text without proper attribution.</td>
        </tr>
      </tbody>
    </table>
    <h3>Why is Plagiarism Wrong?</h3>
    <p>Plagiarism undermines the principles of academic honesty. It deprives the original author of credit for their work, misrepresents your own abilities, and erodes the trust within the academic community. It is essentially intellectual theft.</p>
    <h3>Avoiding Plagiarism</h3>
    <p>The best way to avoid plagiarism is to develop good research and writing habits, properly cite all sources, paraphrase effectively, use quotation marks for direct quotes, and develop your own arguments. Many universities offer plagiarism detection software to help prevent accidental plagiarism.</p>
  </section>

  <!-- Forms Section -->
  <section id="forms">
    <h2>Interactive Form</h2>
    <form>
      <div class="form-section">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name">
      </div>
      <div class="form-section">
        <label>Did you enjoy playing among us?</label>
        <input type="radio" id="yes" name="feedback" value="yes">
        <label for="yes">Yes</label>
        <input type="radio" id="no" name="feedback" value="no">
        <label for="no">No</label>
      </div>
      <div class="form-section">
        <label for="hobbies">Favorite Colors:</label>
        <input type="checkbox" id="reading" name="hobbies" value="reading">
        <label for="reading">Pink</label>
        <input type="checkbox" id="traveling" name="hobbies" value="traveling">
        <label for="traveling">Blue</label>
        <input type="checkbox" id="sports" name="hobbies" value="sports">
        <label for="sports">Red</label>
      </div>
      <div class="form-section">
        <label for="password">Password:</label>
        <input type="password" id="password" name="password">
      </div>
      <div class="form-section">
        <label for="country">Civil Status:</label>
        <select id="country" name="country">
          <option value="philippines">Single</option>
          <option value="usa">Married</option>
          <option value="india">Complicated</option>
        </select>
      </div>
      <button type="submit">Submit</button>
    </form>
  </section>
</body>
</html>

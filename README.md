<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title></title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-image: url:"images (3).jpeg"
      color: white;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: white;
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
      color: green;
      font-weight: bold;
    }
    section {
      margin: 2rem;
    }
    iframe {
      display: block;
      margin: 1rem auto;
      border: 2px solid green;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin: 1rem 0;
    }
    table, th, td {
      border: 1px solid green;
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
    <h1>Macapagal, John Myko</h1>
    <h2>E2 - Computer</h2>
    <audio controls>
      <source src="/lost-in-dreams-abstract-chill-downtempo-cinematic-future-beats-270241.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#blog">Blog</a>
    <a href="#plagiarism">Plagiarism</a>
    <a href="#forms">Forms</a>
  </nav>

  <section id="home">
    <h2>Welcome</h2>
    <p>This webpage is the compilation of my laboratory exercises.</p>
  </section>

  <section id="blog">
    <h2>The Digital Trinity of Threats: Malware, Spam, and Viruses</h2>
    <iframe width="560" height="315" 
            src="https://www.youtube.com/embed/mqzP7gJDM2s" 
            title="YouTube video player" 
            frameborder="0" 
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
    </iframe>
    <p>Our digital lives are constantly under siege. Not by armies of trolls, but by a more insidious enemy: malware, spam, and viruses. Understanding these threats is the first step to protecting yourself.</p>
    <h3>VIRUSES</h3>
    <p>Think of viruses as the original digital bad guys. They're malicious programs that attach themselves to other files, replicating and spreading like, well, a virus. They can corrupt data, slow down your computer, or even crash your system entirely </p>
    <h4>MALWARE</h4>
    <p>This is the broader term encompassing viruses and much more.  Malware is any software designed to damage, disrupt, or gain unauthorized access to your computer.  This includes ransomware (which encrypts your files and demands payment), spyware (which secretly monitors your activity), and adware (which bombards you with unwanted ads).  Malware's reach is far-reaching and its methods constantly evolving.</p>
    <h5>SPAM</h5>
    <p>While not directly harmful to your system in the same way as malware or viruses, spam is still a significant threat.  These unwanted emails, often containing phishing scams or malware links, clog your inbox and can lead to identity theft or system compromise if you're not careful.  Think of spam as the annoying mosquito buzzing around the bigger digital dangers.</p>
    <p>Your Antivirus Arsenal:  Luckily, you don't have to face this digital trinity alone.  Antivirus software is your first line of defense.  A good antivirus program will scan your files for viruses and malware, block suspicious websites, and filter spam emails.  But remember, antivirus software is just one piece of the puzzle.  Staying vigilant, practicing safe browsing habits, and regularly updating your software are equally crucial.</p>
    
  </section>

  <section id="plagiarism">
    <h2>The Shadow of Plagiarism</h2>
    <img src="/plagiarism.png/imgposter.png"
    width="500px" height="300px">
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
    <p>Avoiding Plagiarism:
The best way to avoid plagiarism is to develop good research and writing habits:
- Properly cite all sources: Use a consistent citation style (MLA, APA, Chicago, etc.) and accurately attribute all borrowed ideas and information.
- Paraphrase effectively: Understand the material thoroughly before attempting to restate it in your own words.
- Use quotation marks for direct quotes: Always enclose direct quotations in quotation marks and provide a citation.
- Develop your own arguments: Build upon the research you've conducted to form your own unique perspectives and analyses.
- Use plagiarism detection software: Many universities offer access to tools that can help identify potential instances of plagiarism in your work.
Plagiarism is a serious issue with significant consequences. By understanding what constitutes plagiarism and adopting responsible research and writing practices, you can maintain academic integrity and ensure the originality of your work.</p>
    <p>Plagiarism undermines the principles of academic honesty. It deprives the original author of credit for their work...</p>
  </section>

  <section id="forms">
    <h2>Interactive Form</h2>
    <form>
      <div class="form-section">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name">
      </div>
      <div class="form-section">
        <label for="gender">Does it helpful?</label>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Yes</label>
        <input type="radio" id="No" name="gender" value="female">
        <label for="female">No</label>
      </div>
      <div class="form-section">
        <label for="hobbies">Hobbies:</label>
        <input type="checkbox" id="reading" name="hobbies" value="reading">
        <label for="reading">Reading</label>
        <input type="checkbox" id="traveling" name="hobbies" value="traveling">
        <label for="traveling">Traveling</label>
        <input type="checkbox" id="sports" name="hobbies" value="sports">
        <label for="sports">Cooking</label>
      </div>
      <div class="form-section">
        <label for="password">Password:</label>
        <input type="password" id="password" name="password">
      </div>
      <div class="form-section">
        <label for="country">Country:</label>
        <select id="country" name="country">
          <option value="philippines">Philippines</option>
          <option value="usa">United States</option>
          <option value="canada">India</option>
        </select>
      </div>
      <button type="submit">Submit</button>
    </form>
  </section>
</body>
</html>

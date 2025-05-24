<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Contact Me</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
    }

    .contact-section {
      max-width: 700px;
      margin: 50px auto;
      padding: 40px;
      background-color: #fff;
      border-radius: 12px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
    }

    .contact-section h2 {
      text-align: center;
      margin-bottom: 30px;
      color: #2c3e50;
    }

    .contact-info {
      margin-bottom: 30px;
    }

    .contact-info p {
      margin: 10px 0;
      font-size: 16px;
    }

    .contact-info a {
      color: #2980b9;
      text-decoration: none;
    }

    form input, form textarea {
      width: 100%;
      padding: 12px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 15px;
    }

    form button {
      background-color: #27ae60;
      color: white;
      padding: 12px 20px;
      border: none;
      border-radius: 8px;
      font-size: 16px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    form button:hover {
      background-color: #1e8449;
    }

    .footer {
      text-align: center;
      margin-top: 40px;
      font-size: 14px;
      color: #777;
    }
  </style>
</head>
<body>

  <div class="contact-section">
    <h2>Contact Me</h2>

    <div class="contact-info">
      <p><strong>Email:</strong> <a href="mailto:haroonrasheed1056@gmail.com">haroonrasheed1056@gmail.com</a></p>
      <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/haroonrasheed-ai/" target="_blank">linkedin.com/in/haroonrasheed-ai</a></p>
      <p><strong>GitHub:</strong> <a href="https://github.com/Haroon1056" target="_blank">github.com/Haroon1056</a></p>
    </div>

    <form action="mailto:haroonrasheed1056@gmail.com" method="post" enctype="text/plain">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </div>

  <div class="footer">
    &copy; 2025 Haroon. All rights reserved.
  </div>

</body>
</html>

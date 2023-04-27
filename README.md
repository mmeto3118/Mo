
Frontend
<!DOCTYPE html>
<html>
  <head>
    <title>Gift Application</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <div class="container">
      <h1>Send a Gift Message</h1>
      <form action="/send" method="POST">
        <label for="recipient">Recipient:</label>
        <input type="text" id="recipient" name="recipient" placeholder="Enter recipient's name" required>
        <label for="message">Message:</label>
        <textarea id="message" name="message" placeholder="Enter your personalized message" required></textarea>
        <button type="submit">Send</button>
      </form>
    </div>
  </body>
</html>

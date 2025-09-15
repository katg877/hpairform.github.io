<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Simple Form</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 2rem; }
    form { max-width: 400px; }
    label { display: block; margin-top: 1rem; }
    input, textarea, button {
      width: 100%;
      padding: 0.5rem;
      margin-top: 0.3rem;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background: #28a745;
      color: white;
      border: none;
      cursor: pointer;
      margin-top: 1rem;
    }
    button:hover {
      background: #218838;
    }
  </style>
</head>
<body>
  <h2>Demo Form</h2>
  <form>
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>

    <label for="message">Message:</label>
    <textarea id="message" name="message" rows="5"></textarea>

    <button type="submit">Submit</button>
  </form>
</body>
</html>

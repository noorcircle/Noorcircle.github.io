<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Noor Circle</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet" />
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      padding: 0;
      background: #fffefc;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(to right, #f6d365, #fda085);
      padding: 4rem 2rem;
      text-align: center;
      color: #333;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 0.5rem;
    }

    header p {
      font-size: 1.25rem;
      margin-bottom: 1rem;
    }

    nav {
      margin-top: 1rem;
    }

    nav a {
      margin: 0 12px;
      text-decoration: none;
      font-weight: 600;
      color: #444;
    }

    section {
      max-width: 900px;
      margin: 3rem auto;
      padding: 2rem;
      background: #fffaf3;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
    }

    section h2 {
      color: #f6a823;
      font-size: 1.75rem;
      margin-bottom: 1rem;
    }

    ul {
      padding-left: 1.5rem;
    }

    .cta-button {
      display: inline-block;
      background-color: #f6a823;
      color: white;
      padding: 12px 24px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 1rem;
      margin-right: 10px;
      transition: background 0.3s;
    }

    .cta-button:hover {
      background-color: #d98f1c;
    }

    footer {
      background-color: #f6d365;
      padding: 1rem;
      text-align: center;

# Watch-verse-
Feels like full world of watches
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>WatchVerse</title>
  <style>
    :root {
      --bg: #ffffff;
      --text: #111111;
      --accent: #bfa046; /* gold */
    }* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Helvetica Neue', sans-serif;
  background-color: var(--bg);
  color: var(--text);
  line-height: 1.6;
}

header {
  background: var(--bg);
  padding: 1rem 2rem;
  border-bottom: 1px solid #eee;
  text-align: center;
}

header h1 {
  font-size: 2rem;
  letter-spacing: 1px;
}

nav {
  margin-top: 1rem;
}

nav a {
  text-decoration: none;
  color: var(--accent);
  margin: 0 10px;
  font-weight: bold;
}

.hero {
  padding: 2rem;
  text-align: center;
}

.hero h2 {
  font-size: 1.8rem;
  margin-bottom: 1rem;
}

.hero p {
  color: #444;
  font-size: 1rem;
}

.section {
  padding: 2rem;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
}

.card {
  border: 1px solid #ddd;
  padding: 1rem;
  border-radius: 10px;
  text-align: center;
}

.card img {
  max-width: 100%;
  height: auto;
  border-radius: 8px;
}

.card h3 {
  margin-top: 1rem;
  font-size: 1.2rem;
}

.card button {
  margin-top: 0.5rem;
  background: var(--accent);
  color: white;
  padding: 0.5rem 1rem;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

footer {
  text-align: center;
  padding: 2rem 1rem;
  background: #f9f9f9;
  font-size: 0.9rem;
  color: #555;
}

  </style>
</head>
<body>
  <header>
    <h1>WatchVerse</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#collection">Collection</a>
      <a href="#about">About</a>
    </nav>
  </header>  <section class="hero" id="home">
    <h2>Timeless Elegance, Modern Style

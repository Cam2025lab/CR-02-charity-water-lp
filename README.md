<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Charity: Water Ad</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="ad-container">
    <div class="overlay">
      <div class="logo">charity: water</div>
      <div class="content">
        <h1>Change the World<br>Between Classes</h1>
        <p>Your donation brings clean water directly to communities in need—clean water, real impact, your move.</p>
        <button class="donate-button">GIVE</button>
      </div>
    </div>
  </div>
</body>
</html>

css
Copy
Edit
body {
  margin: 0;
  font-family: Arial, sans-serif;
}

.ad-container {
  background-image: url('https://i.imgur.com/FtxCR49.jpg'); /* Replace with your own or host the real one */
  background-size: cover;
  background-position: center;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  position: relative;
}

.overlay {
  background: rgba(0, 0, 0, 0.4); /* slight dark overlay */
  padding: 40px;
  border-radius: 10px;
  max-width: 500px;
}

.logo {
  font-weight: bold;
  font-size: 20px;
  margin-bottom: 20px;
  color: #FFD700; /* gold-like color */
}

.content h1 {
  font-size: 28px;
  margin: 0 0 15px 0;
}

.content p {
  font-size: 16px;
  margin-bottom: 20px;
}

.donate-button {
  background-color: #FFD700;
  border: none;
  padding: 12px 25px;
  font-size: 16px;
  font-weight: bold;
  cursor: pointer;
  border-radius: 5px;
  color: black;
}

.donate-button:hover {
  background-color: #e6c200;
}

## charity: water Brand Colors & Fonts

### Primary Colors:
- Yellow:     `#FFC907`
- Blue:       `#2E9DF7`

### Secondary Colors:
- Light Blue: `#8BD1CB`
- Green:      `#4FCB53`
- Orange:     `#FF902A`
- Red:        `#F5402C`
- Dark Green: `#159A48`
- Pink:       `#F16061`

### Fonts:
- Proxima Nova
- Avenir

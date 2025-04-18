/* css/style.css */
body {
  font-family: 'Noto Sans Bengali', 'Roboto', sans-serif;
  margin: 0;
  background-color: #fff7ed;
  color: #333;
}

header {
  background-color: #ff6f00;
  color: white;
  text-align: center;
  padding: 20px 10px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.2);
}

nav {
  background-color: #ffcc80;
  padding: 10px;
  text-align: center;
}

nav a {
  margin: 0 15px;
  color: #4e2600;
  text-decoration: none;
  font-weight: bold;
}

main {
  padding: 20px;
  max-width: 1000px;
  margin: auto;
}

h2 {
  color: #d84315;
  border-bottom: 2px solid #ffcc80;
  padding-bottom: 5px;
}

.menu-item {
  margin-bottom: 25px;
  background-color: #fff3e0;
  padding: 15px;
  border-radius: 10px;
  box-shadow: 0 1px 4px rgba(0,0,0,0.1);
}

.menu-item img {
  width: 100%;
  max-height: 250px;
  object-fit: cover;
  border-radius: 10px;
  margin-bottom: 10px;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
  gap: 15px;
  margin-top: 15px;
}

.gallery img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-radius: 10px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.whatsapp-button {
  display: inline-block;
  padding: 12px 25px;
  background-color: #25d366;
  color: white;
  font-weight: bold;
  text-decoration: none;
  border-radius: 30px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.2);
  margin-top: 15px;
}

footer {
  background-color: #ff6f00;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 30px;
}

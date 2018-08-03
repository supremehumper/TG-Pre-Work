body {
  background-color: white;
  font-family: 'Raleway', sans-serif;
}

.navigation ul {
  margin: 0;
  padding: 0;
  text-align: center;
}

.navigation li {
  font-weight: 100;
  letter-spacing: 2px;
}

.navigation  li.logo {
  color: black;
  font-size: 18px;
  font-weight: 700;
  letter-spacing: 4px;
}

#banner {
  background-image: url("https://s3.amazonaws.com/codecademy-content/courses/web-101/unit-6/htmlcss1-img_tahoe.jpeg");
  background-size: cover;
  background-position: bottom center;
  width: 100%;
  height: 700px;
}

#banner .content h1 {
  position: relative;
  top: 50px;
  margin: 0 auto;
  width: 400px;
}

#main {
  padding: 40px;
  text-align: center;
  width: 400px;
}

h1 {
  color: white;
  font-size: 42px;
  font-weight: 600;
  text-align: center;
}

h2 {
  color: red;
  font-size: 14px;
  line-height: 48px;
  text-align: center;
}

h3 {
  color: red;
  font-size: 26px;
  font-weight: 700;
  padding: 20px 10px;
}

p {
  color: grey;
  font-size: 16px;
  line-height: 48px;
}

.pull-quote {
  width: 350px;
}

.byline {
  border-bottom: 1px solid LightGrey;
  border-top: 1px solid LightGrey;
  color: DarkGrey;
  font-size: 14px;
  font-weight: 200;
}

.share {
  border: 1px solid LightGrey;
  padding: 40px 0px;
  position: relative;
  text-align: center;
  width: 100%;
}

.share a {
  background: red;
  border: 1px solid red;
  border-radius: 3px;
  color: white;
  display: inline-block;
  text-decoration: none;
}

.share a:hover {
  background: white;
  border: 1px solid red;
  color: red;
}
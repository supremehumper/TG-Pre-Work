/* Universal Styles */

html {
  font-size: 16px;
  font-family: "Arial", sans-serif;
}

body {
  background-color: #F2F2F2;
}

h1 {
  color: white;
  font-size: 28px;
}

h2 {
  font-size: 24px;
  font-weight: 700;
  line-height: 2.5;
}

h1, h2 {
  font-family: Georgia;
}

a {
  text-decoration: none;
}

p {
  margin: 16px 0;
  font-family: Helvetica;
}

strong {
  font-weight: bold;
}

#serif, /* Offset linked sections to account for header. */
#sans,
#mono {
  padding-top: 77px;
  margin-top: -77px;
}

/* Header */

.header {
  font-family: "Arial", sans-serif;
  font-size: 14px;
  line-height: 1.25;
  background-color: #fff;
  position: fixed;
  top: 0;
  width: 100%;
}

.header li {
  display: inline-block;
}

.header a {
  display: block;
  color: #4A4A4A;
  padding: 30px 20px;
}

a.home {
  color: #4D00FF;
}


/* Banner Section */

.banner {
  background-color: #4D00FF;
  padding: 100px 0;
  margin-top: 77px;
  text-align: center;
}

.banner p {
  border-top: 1px solid #fff;
  border-bottom: 1px solid #fff;
  padding: 10px;
  color: #ffffff;
}

/* Editorial Sections */

.editorial {
  padding: 20px;
  margin: 20px 0;
  text-align: center;
  color: #4C4C4C;
}

/* Font Card Sections */

.font-card {
  background-color: #ffffff;
  margin: 50px 0;
  padding: 20px 50px;
}

.font-card .creator {
  font-size: 20px;
  line-height: 1.25;
}

.sample {
  display: inline-block;
  padding: 0 20px;
  margin: 20px;
}

.sample h2 {
  line-height: 1.5;
}

.sample .text {
  color: #4D00FF;
  font-size: 100px;
}

/* Add styles for the Garamond font here */

/* Add styles for the Helvetica font here */

/* Add styles for the Space Mono font here */

.bold {
  font-weight: 900;
}

.regular {
  font-weight: normal;
}

.italic {
  font-weight: normal;
  font-style: italic;
}

/* Media Queries */

@media only screen and (max-width: 535px) {
  .header {
    font-size: 14px;
  }

  .header a {
    padding: 30px 20px;
  }

  a.home {
    display: none;
  }
}

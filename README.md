.container {
  display: grid;
  max-width: 900px;
  position: relative;
  margin: auto;
  grid-gap: 10px;
  grid-template: repeat(12, 1fr) / repeat(6, 1fr);
}

h1, h2, h3 {
  font-family: monospace;
  text-align: center;
}

header {
  background-color: dodgerblue;
  grid-area: 1 / 1 / 3 / 7;
}

nav {
  background-color: beige;
  grid-area: 3 / 1 / 4 / 7;
}

.left {
  background-color: dodgerblue;
  grid-area: 4/1/9/5;
}

.right {
  background-color: beige;
  grid-area: 4/5/9/7;
}

.overlap {
  background-color: lightcoral;
  grid-area: 6/4/8/6;
  z-index: 5;
}

footer {
  background-color: dodgerblue;
  grid-area: 9/1/13/7;
}
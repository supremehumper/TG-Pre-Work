.grid {
  display: grid;
  border: 2px blue solid;
  height: 500px;
  width: 500px;
  grid-template: repeat(4, 1fr 2fr) / repeat(4, 3fr 2fr);
  grid-gap: 5px;
}

.a {
  grid-area: 5 / 1 / span 2 / span 2;
}

.b {
  grid-area: 2 / 2 / span 3 / span 6;
}

.c {
  grid-area: 6 / 8 / span 3 / span 1;
}

.box {
  background-color: beige;
  color: black;
  border-radius: 5px;
  border: 2px dodgerblue solid;
}
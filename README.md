.grid {
  display: grid;
  border: 2px blue solid;
  height: 500px;
  width: 500px;
  grid-template: repeat(4, 1fr 2fr) / repeat(4, 3fr 2fr);
  grid-gap: 5px;
}

.a {
  grid-row-start: 5;
  grid-row-end: 7;
}

.box {
  background-color: beige;
  color: black;
  border-radius: 5px;
  border: 2px dodgerblue solid;
}
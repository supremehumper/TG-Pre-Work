header, footer {
  background-color: #ffa500;
  text-align: center;
  min-width: 500px;
}

main {
  display: grid;
  grid-template-columns: 250px 250px;
  grid-template-rows: repeat(3, 450px);
  grid-gap: 20px;
  margin-top: 44px;
  grid-auto-rows: 500px;
  justify-items: center;
  justify-content: center;
}

h2 {
  font-family: Poppins;
  font-size: 18px;
  font-weight: 600;
  letter-spacing: 0.3px;
  text-align: left;
  color: #ffa500;
  padding: 10px 0px 10px 10px;
}

img {
  width: 100%;
  height: auto;
}

.recipe {
  box-shadow: 0 1px 1px 0 rgba(0, 0, 0, 0.5);
  width: 200px;
}

.a {
  
}

.c {
  
}

.time {
  padding-left: 10px;
  padding-top: 10px;
  width: 20px;
  height: auto;
}

.mins {
  display: inline-block;
  font-family: Poppins;
  font-size: 14px;
  font-weight: 500;
  letter-spacing: 0.3px;
  text-align: left;
  color: #4a4a4a;
  position: relative;
  bottom: 5px;
}

.description {
  font-family: Work Sans;
  font-size: 14px;
  font-weight: 300;
  line-height: 1.29;
  letter-spacing: 0.1px;
  text-align: left;
  color: #4a4a4a;
  padding: 10px 0px 10px 10px;
  border-top: 1px solid #4a4a4a;
}

.logo {
  width: 115px;
  height: 21.1px;
  object-fit: contain;
  padding: 20px;
}

.container {
  min-width: 500px;
  margin: auto;
}

footer {
  margin-top: 44px;
}
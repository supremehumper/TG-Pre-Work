const satellite = 'The Moon';
const galaxy = 'The Milky Way';
let stars = 'North Star';

const myNightSky = (satellite, galaxy, stars) => {
  stars = 'Sirius';
  return 'Night sky: ' + satellite + ', ' + stars + ', ' + galaxy;
}

console.log(myNightSky());
console.log(stars);
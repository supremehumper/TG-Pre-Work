let groceryList = ['orange juice', 'bananas', 'coffee beans', 'brown rice', 'pasta', 'coconut oil', 'plantains'];

let fridge = [];

while (fridge.length < groceryList.length) {
  for (let i = 0; i < groceryList.length; i++) {
    fridge.push(groceryList[i]);
  }
}
console.log(fridge);

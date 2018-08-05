const takeOrder = (topping, crustType) => {
  console.log('Order: ' + crustType + ' crust pizza topped with ' + topping);
};

takeOrder();
takeOrder('cheese', 'thin');
takeOrder('pepperoni', 'thick');
takeOrder('onions', 'new york style');
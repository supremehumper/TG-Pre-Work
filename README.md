let person = {
  _name: 'Lu Xun',
  _age: 137,
  
  set age(age) {
    if (typeof age === 'number') {
      this._age = age;
    } else {
      return 'Invalid input';
    }
  },
  
  get age() {
    console.log('${this.name} is ${this.age} years old.');
  }
}

person.age = 'Thirty-nine';
person.age = 39;
console.log(person.age);

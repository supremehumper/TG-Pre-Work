let person = {
  _name: 'Lu Xun',
  _age: 137,
  
  set age(age) {
    if (typeof age === 'number') {
      this._age = this.age;
    } else {
      return 'Invalid input';
    }
  }
};


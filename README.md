let person = {
  name: 'Alex',
  age: 40,
  weekendAlarm: 'No alarms needed',
  weekAlarm: 'Alarm set to 7AM',
  sayHello() {return `Hello, my name is ${this.name}`},
  sayGoodbye() {return 'Goodbye!'},
}

let friend = {
  name: 'Kory Sibert',
}

friend.sayHello = person.sayHello;

let day = 'Sunday';
let alarm;

if (day === 'Saturday' || day === 'Sunday') {
  alarm = 'weekendAlarm';
} else {
  alarm = 'weekAlarm';
}

person.hobbies = ['Learning to code', 'Coding to learn'];

console.log(person['name']);
console.log(person['age']);
console.log(alarm);
console.log(person[alarm]);
person.hobbies.pop();

console.log(person.hobbies);
console.log(person.sayHello());

console.log(friend.sayHello());




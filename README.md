let person = {
  name: 'Tyron',
  age: 40,
  weekendAlarm: 'No alarms needed',
  weekAlarm: 'Alarm set to 7AM',
}

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
console.log(person.hobbies);
# Dart Memo

## if - else - else if
```dart
if (someCondition) {
// code block
}
```
```dart
const animal = 'Fox';
if (animal == 'Cat' || animal == 'Dog') {
print('Animal is a house pet.');
} else {
print('Animal is not a house pet.');
}
```
```dart
const trafficLight = 'yellow';
var command = '';
if (trafficLight == 'red') {
command = 'Stop';
} else if (trafficLight == 'yellow') {
command = 'Slow down';
} else if (trafficLight == 'green') {
command = 'Go';
} else {
command = 'INVALID COLOR!';
}
print(command);
```
## switch
```dart
switch (variable) {
case value1:
// code
break;
case value2:
// code
break;
...
}
default:
// code
```
## string interpolation
```dart
const name = 'Bondi';
const introduction = 'Hello my name is $name';
// 'Hello my name is Bondi'
```
## ternary operator
```dart
(condition) ? valueIfTrue : valueIfFalse;
```
## switch

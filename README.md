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
## enums
```dart
enum Weather {
sunny,
snowy,
cloudy,
rainy,
}
```
```dart
const weatherToday = Weather.cloudy;
switch (weatherToday) {
case Weather.sunny:
print('Put on sunscreen.');
break;
case Weather.snowy:
print('Get your skis.');
break;
case Weather.cloudy:
case Weather.rainy:
print('Bring an umbrella.');
break;
}
print(weatherToday);
// Weather.cloudy
final index = weatherToday.index;
// 2
```
## while
```dart
sum = 1;
while (true) {
sum += 4;
if (sum > 10) {
break;
}
}
```
## do while
```dart
sum = 1;
do {
sum += 4;
print(sum);
} whil
```
## for
```dart
for (var i = 0; i < 5; i++) {
print(i);
}
```
```dart
for (var i = 0; i < 5; i++) {
if (i == 2) {
continue; // skip 2
}
print(i);
}
```

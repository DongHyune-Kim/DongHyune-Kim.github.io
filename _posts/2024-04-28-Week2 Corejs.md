---
layout: single
title: "2주차 CoreJavaScript 실습 예제입니다."
---

# Example 1-1 변수 선언
```js
var a;
```
# Example 1-2 변수 선언과 할당
```js
var a; 
a = 'abc';

var a = 'abc';
```
# Example 1-3 불변성
```js
var a = 'abc';
a = a + 'def';

var b = 5;
var c = 5;
b = 7;
```
# Example 1-4 참조형 데이터의 할당
```js
var obj1 = {
  a: 1,
  b: 'bbb',
};
```
# Example 1-5 참조형 데이터의 프로퍼티 재할당
```js
var obj1 = {
  a: 1,
  b: 'bbb',
};
obj1.a = 2;
```
# Example 1-6 중첩된 참조형 데이터(객체)의 프로퍼티 할당
```js
var obj = {
  x: 3,
  arr: [3, 4, 5],
};
```

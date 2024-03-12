---
layout: page
permalink: /js学习笔记 1/blogs.html
title: js学习笔记 1
---

## js学习笔记 1

>// 创建一个空对象
>var person = {};
>
>// 添加属性到对象
>person.name = "John";
>person.age = 30;
>person.gender = "male";
>
>// 访问对象的属性
>console.log(person.name);  // 输出 "John"
>console.log(person["age"]); // 输出 30
>
>// 修改对象的属性
>person.age = 31;
>
>// 删除对象的属性
>delete person.gender;
>
>// 定义一个包含方法的对象
>var car = {
>    brand: "Toyota",
>    model: "Camry",
>    year: 2020,
>    start: function() {
>        console.log("Engine started.");
>    },
>    stop: function() {
>        console.log("Engine stopped.");
>    }
>};
>
>// 调用对象的方法
>car.start(); // 输出 "Engine started."
>car.stop();  // 输出 "Engine stopped."


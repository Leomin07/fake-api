## TRAN DAI MINH 08-04

## TOPIC: Array, Linked list, Queue, Stack, Hash table, Set, Tree, Graph, AJAX and JSON, promise, async await syntax, ajax request (Fetch API, Axios), scope, arrow function, template string, destructuring, default parameter, rest, spread.

- AJAX Là viết tắt của cụm từ Asynchronous Javascript and XML. Là phương thức trao đổi dữ liệu với máy chủ và cập nhật một hay nhiều phần của trang web giúp chúng ta tạo ra sự sinh động cho Website của mình mà không reload lại trang.

- JSON là chữ viết tắt của Javascript Object Notation, là một dạng dữ liệu tuân theo một quy luật nhất định mà hầu hết các ngôn ngữ lập trình hiện nay đều có thể đọc được, bạn có thể sử dụng lưu nó vào một file, một record trong CSDL rất dễ dàng.

- promise
- async await syntax
- ajax request (Fetch API, Axios)
- **arrow function** là cú pháp ngắn ngọn hơn để dùng **function**, sử dụng **=>**.

```
const person = (name,age) => {
    console.log('Name:'+ name + age +years old);
}
person('Minh',18);
//expected output: Name: Minh 18 years old;
```

- **template string** là cách mà chúng ta tạo ra một string dễ dàng hơn với các biến, biểu thức bên trong string.

```
const name = 'Minh';
var person = `My name is ${name} `;
```

- **destructuring** là một cú pháp cho phép tách dữ liệu được lưu trữ bên trong Objects hoặc Arrays và gán chúng cho các biến riêng biệt.

```js
//destructuring object
const person = { name: 'Minh', age: 20 };
const { name, age } = person;
console.log(name); // expected output: Minh
console.log(age); // expected output: 20

//destructuring array
const animal = ['dog', 'cat'];
const [one, two] = animal;
console.log(one); // expected output: dog
console.log(two); // expected output: cat
```

- default parameter
- rest
- spread

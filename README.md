## FAKE API

## TRAN DAI MINH 08-03

## TOPIC: this, apply, call, bind, setTimeout/clearTimeout, setInterval/clearInterval.

- This: từ khoá **this** trong Javascript đề cập đến đối tượng mà ó thuộc về.

```
const test = {
  prop: 42,
  func: function() {
    return this.prop;
  },
};

console.log(test.func());
// expected output: 42
```


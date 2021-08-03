## FAKE API


- SetInterval/ClearInterval:

  - **SetInterval** hàm này sẽ thường được sử dụng để thiết lập độ trễ cho các hàm sẽ được thực hiện lặp lại như là hiệu ứng.

  - Syntax: **setInterval(function, milliseconds, param1, param2, ...)**

  ```
    var intervalId = setInterval(function(){ alert("Hello"); }, 3000);
    // expected output: alert("Hello");
  ```

  - **ClearInterval** sẽ xóa đi nhiệm vụ mà ta đã thiết lập trong hàm **setInterval()**

  - Syntax: clearInterval(mySetInterval);

  ```
    clearInterval(intervalId);
  ```



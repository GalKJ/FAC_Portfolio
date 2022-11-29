# HTTP Portfolio

---

## 1. Write code that executes asynchronously

![image](https://user-images.githubusercontent.com/99536044/204624444-18e3fcc3-a280-4e5d-baed-010a5d5eb407.png)

- The code above uses an `async` function and the `await` operator which is used to wait for a Promise and get its fulfillment value.

---

## 2. Use callbacks to access values that aren’t available synchronously

- The code on line 84 in the above screenshot is an example of an asynchronous callback `randomPostcodeButton.addEventListener('click', (randomPostcodeGenerator));` since the event listener waits for the `'click'` event before calling the `randomPostcodeGenerator` async function. 

## 
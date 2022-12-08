# HTTP Portfolio

---

## 1. Write code that executes asynchronously

![image](https://user-images.githubusercontent.com/99536044/204624444-18e3fcc3-a280-4e5d-baed-010a5d5eb407.png)

- The code above uses an `async` function and the `await` operator which is used to wait for a Promise and get its fulfillment value.

---

## 2. Use callbacks to access values that aren’t available synchronously

- The code on line 84 in the above screenshot is an example of an asynchronous callback `randomPostcodeButton.addEventListener('click', (randomPostcodeGenerator));` since the event listener waits for the `'click'` event before calling the `randomPostcodeGenerator` async function. 

---

## 3. Use promises to access values that aren’t available synchronously

- The `async` and `await` keywords used in the above screen shot enable asynchronous, promise-based behavior to be written in a cleaner style, avoiding the need to explicitly configure promise chains. By using promises we can wait for the promise to be settled (that is, fulfilled or rejected) while we continue to run our synchronous code.

![image](https://user-images.githubusercontent.com/99536044/205118853-11f552c0-dab3-4202-b858-b5db61543fce.png)

- We can also use the `fetch()` method with `.then` to chain our promises togther keeping our code readable.

---

## 4. Use the fetch method to make HTTP requests and receive responses

- On lines 11, 13 and 15 the `fetch()` method is being used to make a HTTP request and when that promise is fullfilled it's retuned and it's handling is defered to the next `.then` handler. 

---

## 5. Configure the options argument of the fetch method to make GET and POST requests

![image](https://user-images.githubusercontent.com/99536044/205127666-f61a1644-11ae-488c-a58b-ad457786498a.png)

---

## 6. Use the map array method to create a new array containing new values

![image](https://user-images.githubusercontent.com/99536044/206536863-db30abdc-f9ac-4572-ab36-8ba53a5957a1.png)

---

## 7. Use the filter array method to create a new array with certain values removed

![image](https://user-images.githubusercontent.com/99536044/206537995-3a7e6bb4-4362-498d-a4b1-b181ff133e38.png)

---

## 8. Access DOM nodes using a variety of selectors





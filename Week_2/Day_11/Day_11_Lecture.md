## Day 11 Lecture Notes: Nov 24, 2022

* Promise object:
    * States: pending, resolve, reject
    * Always has two params, resolve (1st) and reject (2nd)
    * When consuming object, use .then for resolve and .catch for reject
    * We don’t always have to create the promise, most of the time it’s built in and we can just consume it when calling the function where the promise is built into
    * If you have multiple promises needed, we can use Promise.all([array of function calls]) then use a single .then and .catch

### Links

* [Code demo - callback hell](https://gist.github.com/DominicTremblay/311014069b5ce616b5ccf4792a362910#file-callback_hell-js)
* [Code demo - other](https://github.com/DominicTremblay/w10-kickoff-lecture)
* [Lecture recording](https://vimeo.com/774882876/f1263c4294)
* [Breakout recording](https://vimeo.com/774881840/00ea6f1762)
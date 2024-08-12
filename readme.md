$ npm install --global jfcm-palindrome
$ vim test.js
let Phrase = require("jfcm-palindrome");
let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
console.log(napoleonsLament.palindrome());
$ node test.js
true
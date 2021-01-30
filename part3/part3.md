# Part 3.1
1. The bug was the number inputs had the data type of string, so the attempt to add in the function calculateSum was a concatenation instead
2. Replace line 9 with:
   ```javascript
   let result = Number(num1) + Number(num2);
   ```
   (I use firefox so I can't edit the javascript from the browser)

# Part 3.2
1. citylots.json
2. part2.js
3. 11.15 MB
4. 633 ms
5. Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:84.0) Gecko/20100101 Firefox/84.0
6. Apache
7. Tue, 26 Jan 2021 22:14:13 GMT
8. application/json
9. fetchData in part2.js
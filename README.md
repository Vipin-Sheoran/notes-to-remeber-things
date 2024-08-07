# notes-to-remeber-things
1. In Javascript 0/0 is NaN.
2. Code to Arrange Array in Ascending order
   ```
   const sortAsc = (arr: number[]) => {
   for(let i = 0; i < arr.length; i++) {
      for(let j = 0; j < arr.length - 1; j++) {
        if(arr[j] > arr[j + 1]) {
         const curr = arr[j]
         arr[j] = arr[j + 1]
         arr[j + 1] = curr
        }
      }
   }
   return arr;
   }
3. - Any value in JavaScript that is not a primitive (string, number, boolean, symbol, null, or undefined) is considered an object. This includes arrays, functions, dates, regex, etc.
   - A plain object refers to an object that is created directly from the Object constructor or object literal syntax {} without a prototype chain other than the base Object.prototype.
4. ```sudo lsof -i :3000```
   code to find PID of a port running on your device
   ```kill -9 PID```
   to kill that port
   

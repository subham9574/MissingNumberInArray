# MissingNumberInArray 
Checking for missing number

function missingNumber(arr) {
  var n = arr.length + 1;
  var sum = 0;
  //GaussLaw
  var sumUptoN = (n * (n + 1)) / 2;
  for (var i = 0; i < n - 1; i++) sum = sum + arr[i];

  return sumUptoN - sum;
}
console.log(missingNumber([1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 14]));


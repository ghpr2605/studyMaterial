// Q. IMPLEMENT LOGIC TO PERFORM ARRAY ROTATION BY SPECIFIED NO. OF POSITION.
//e.g. arr = [1,2,3,4,5] n =3
// So here array arr need to be rotated by 3 position
//o/p = [3,4,5,1,2]

var arr, pos, n;

arr = [1,2,3,4,5,6,7,8,9]; // i/p array
pos = 3; //No. of position to be shifted
n = pos % arr.length; //Using mod we reduce the number of loop

//e.g for 3 & 12 in this example looping 12 times is not good hence use mode which returns 3 and ultimately same output

for(i = 0; i < n; i++){
  //As it is circular rotation, order must be preserved. So using pop we   extract the last element and using unshift we append it at the           beginning until req. no. of pos are not shifted
  
  arr.unshift(arr.pop());
}

console.log(arr);


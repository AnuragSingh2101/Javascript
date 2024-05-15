# Javascript
// For of Loop
const arr = [1,2,3,4,5]
for (const i of arr) {
//    console.log(i);
}


//Maps
const map = new Map()
map.set('IN' , "INDIA");
map.set('AF' , "AFRICA");
map.set('AUS' , "AUSTRALIA");
//  console.log(map);

for (const key of map) {
//    console.log(key);    
}

for (const [key , value] of map) {
//    console.log(key, ':-', value);    
}

const myNums = [1,2,3,4,5,6,7,8,9,10]
const newNums = myNums.filter( (num) => num > 4)
console.log(newNums);

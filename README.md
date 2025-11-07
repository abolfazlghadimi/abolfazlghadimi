console.group('A')
console.log('abolfazl')
console.groupEnd
console.warn('warning...')
const style='padding:10x; background-color:red'
console.log('%cJavascript',style)
let product={
name:'RAM16',
price:100,
instock:true,
}
console.log(product)

let products=[
    {name:'BMW',price:900000},{name:'Benz',price:80000},{name:'pride',price:10},{name:'mazda',price:100}
]
console.log(products)

let flowers=[
    {name:'ROZ',color:'yellow'},{name:'LALE',color:'pink'},{name:'mikhak',color:'red'},{name:'orkideh',color:'purple'},{name:'maryam',color:'white'}
]
console.log(flowers)

let temperture=15;

let tempertures = temperture>20 ? 'HOT' :'COLD'

console.log(tempertures)
function addnumber(num1,num2){
    return num1+num2
}
console.log
(addnumber(4+3))
for (let i=10; i<=100; i+=10){
    console.log(i);
}
let  colors =['RED' , 'blue' , 'pink'];

for (let color of colors) {
    console.log(color);
}


















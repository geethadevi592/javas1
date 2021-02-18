# javas1
### Functions
Functions With out Parameters
```javascript
function addition(){
var a=10;
var b=20;
return a+b;
}
addition()
30
```
FUNCTIONS WITH PARAMETERS

```javascript
function addition(a,b){
return(a+b)
}
addition(3,6)

9
```javascript
function multiplication(a,b){
return(a*b)
}
multiplication(3,6)

18
```
Anonamus Functions
```javascript
var sub=function(a,b){
return (a-b)
}
undefined
```javascript
var mul=(a,b)=>{
return (a*b)
}
mul(6,9)
54
```
#### Higher oerder functionns(HOF)
*A Function accepts another function as an arugument*
arr.map((item,index)=>{
console.log(item+" is having index of :"+index)
})


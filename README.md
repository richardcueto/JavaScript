# Codigo JavaScript

Se colocara fragmentos del codigo de JavaScript para porder tener un second brain

## Prerequisites:
- Visual Studio Code
- Navegador Web

### License
Creative Commons (CC BY 4.0)

# Examples
## Expresiones regulares
```javascript 
let cadena="Lorem fine loremipsos 9";
// let expReg=new RegExp("lorem","ig");
// console.log(expReg.test(cadena));
// console.log(expReg.exec(cadena));

//let expReg2=/\d/;//numero
let expReg2=/lorem{1}/ig;//numero
console.log(expReg2.test(cadena));
console.log(expReg2.exec(cadena));
```
## Funciones anónimas autoejecutadas
```javascript
//funciones autoejecutable
(function(){
   console.log("mi primer IIFE");
})();

(function(w,d,c){
   console.log("mi segunda IIFE");
   console.log(w);
   c.log(d);
})(window,document,console);
```

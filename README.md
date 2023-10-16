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
## Importar modulos
```html
<!DOCTYPE html>
<html lang="en">

<head>
 <meta chraset="UTF-8">
 <meta name="viwport" content="width=device-with,initial-scale=1.">
 <title>Fundamentos Java script</title>
</head>

<body>
   <script src="js/modulos.js" type="module"></script>
   <script src="js/no-modulos.js" nomodule ></script>
</body>

</html>
```

```javascript
import password,{pi,usuario} from "./constantes.js"
import {aritmetica as cal} from "./aritmetica.js"
console.log("first to he");
console.log(pi,usuario);
console.log(cal.sumar(42,1));
console.log(cal.restar(0,1));
console.log(password)
```

```javascript
console.log("mi navegador no soporta +ES6")
```

```javascript
export const pi=Math.PI;

export let usuario="richard";

const password="qwerty";
export default password;

// export default function saludar(){//solo se puede tener un solo default
//     console.log("hola mundo +ES6");
// }
```

```javascript
function sumar(a,b){
    return a+b;
}
function restar(a,b){
    return a-b;
}
export const aritmetica={
    sumar,
    restar
}
```

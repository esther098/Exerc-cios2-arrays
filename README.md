# Exerc-cios2-arrays
// 1
function concatenar (a,b){
 
  const aMaisb= a.concat(b)
  return aMaisb
}
var c= ['picole','gelatto', 'geladinho']
var d=['morango', 'chocolate', 'banana']
console.log(concatenar(c,d))

//2
var numeros=[1,2,3,4,5,6,7,8,9,10]
var parteNumeros=numeros.slice(3,8)
console.log(parteNumeros)

//3
const frutas = ['Maçã', 'Banana', 'Laranja', 'Limão', 'Abacaxi']

frutas.splice(2,2,'Kiwi','Pêssego')
console.log(frutas)

//4
 var menuPrincipal =['omelete','salmão','espetinho','bacalhau']
 var menuDeSobremesas=['sorvete','gelatina','pudim','torta']
 var MenuCompleto= menuPrincipal.concat(menuDeSobremesas)
 
 console.log(MenuCompleto)

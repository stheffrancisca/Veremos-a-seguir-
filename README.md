# Veremos-a-seguir-
Como verificar se uma condição é falsa (ou não verdadeira)?


var c = 3;
var d = 5;
var e = false; // valores possíveis -> True, False

console.log("if com mais de duas condições e combinação de && e ||:");
if ((c > d && d > 0) || (c > d && d <= 0)){
    console.log("c é maior que d E d é um número positivo");
    console.log("OU");
    console.log("c é maior que d E d não é um número positivo");
}
console.log("if com condição não verdadeira:");
if (!e){
    console.log("e tem valor false");
}

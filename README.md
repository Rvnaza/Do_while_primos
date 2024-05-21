/*2) Os números primos possuem várias aplicações dentro da Computação, por exemplo, na criptografia. Um número primo é aquele que é divisível apenas por um e por ele mesmo. Faça um programa que peça ao usuário para digitar cinco números inteiros e mostre na tela se são primos ou não.*/

let numeroUm, contador = 2
let cont = 0

while(cont < 5){
    numeroUm = Number(prompt('Digite o número: '))
    cont++
    do{

if(numeroUm%contador == 0){
    break}
    contador++
}while(contador < numeroUm)

if(contador == numeroUm){
    alert('O número '+numeroUm+' é primo.')
}else{
    alert('O número '+numeroUm+' não é primo.')
    
} contador = 2
}

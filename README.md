# triangulo
Algoritmo "triangulo" 
// Disciplina   : [PA] 
// Professor   : Cintia pinho
// Descri��o   : V� qual � o tipo de triangulo 
// Autor(a)    : Luis Fernando Osuna Solda
// Data atual  : 24/11/2021 
Var
a,b,c: real 


Inicio
//entrada 
escreval ("digite o primeiro lado do triangulo")
leia (a) 
escreval ("Digite o segundo lado do triangulo") 
leia (b) 
escreval ("digite o terceiro lado do triangulo") 
leia(c)

se((a&lt;(b+c))e(a>(abs(b-c)))))e((b&lt;(a+c))e(b>(abs(a-c))))e(c>(abs(b-a))))entao
    se ((a-b) e (b-c) e (a-c)) entao 
    escreval("triangulo equilatero") 
fimse  
se((a&lt;>b)e(b&lt;>c) e (a&lt;>c)) entao   
escreval ("triangulo escaleno")    
fimse 
se(((a-b) e (b&lt;>c)) ou ((b-c) e (c&lt;>a)) ou ((a-c) e (c&lt;>b)) ) entao 
escreval("triangulo isoceles")   
fimse 
senao     
escreval("valores nao forma um triangulo") 
fimse 
Fimalgoritmo 

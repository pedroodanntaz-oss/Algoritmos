# Algoritmos
Atividade de Lógica de programação 
algoritmo "Simulador_CDB"
var
   valor, taxa : real
   prazo : inteiro
inicio
   escreva("Digite o valor do investimento: ")
   leia(valor)

   escreva("Digite o prazo em meses: ")
   leia(prazo)

   se (prazo > 12) entao
      taxa <- 0.12
   senao
      taxa <- 0.08
   fimse

   escreva("Taxa aplicada: ", taxa * 100, "% ao ano")
fimalgoritmo

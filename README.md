# Desafio-Publica
VISUALG 2.0

algoritmo "Pontuação no Basquete"
// Função :
// Autor : Igor Maciel da Costa Machado
// Data : 04/10/2020
// Seção de Declaração

var
i:inteiro
pontos:inteiro
mintemporada: inteiro
maxtemporada: inteiro
 
 
inicio
escreval ("dgite seu recorde de ponuação minima")
leia ( mintemporada)
escreval("---------")
escreval( "dgite seu recorde de pontuação maxima")
leia ( maxtemporada)
limpatela

escreval("digite o placar")
 leia(pontos)
 limpatela
 se (pontos)< (mintemporada)entao
   escreval("Bateu recorde Minimo da Temporada")
 senao
   escreval ("Não bateu recorde minimo")
  fimse
 se (pontos) > (maxtemporada) entao
    escreval("Bateu recorde Máximo da temporada")
  senao
     escreval("Não bateu recorde máximo")
     fimse


fimalgoritmo

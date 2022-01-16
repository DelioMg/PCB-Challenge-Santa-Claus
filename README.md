# PCB-Challenge-Santa-Claus
Projeto de PCB desenvolvido para o Julialabs PCB Challange 2021, em que mostra as roupas que o Papai Noel usa em lugares muito quentes.

A placa consiste em um attiny85 ligado ao um cd4511 para controlar 14 leds de tres cores:
- 4 leds laranja que vão da iluminação de fundo.
- 5 leds azul  que vai iluminar os símbolos da camisa.
- 4 leds vermelhos para iluminar a frente da PCB

Os leds escolhidos são para aplicações de baixo consumo devido a alimentação ser por uma bateria CR2030, pois os mesmo prometem entregar com 2mA a mesma luminosidade que um led comum consome a 20mA, em que eles forma ligados os pares em serie no cd4511 para aproveitando a tensões deles e utilizar menos saídas. 

Em que foi utilizado attiny85 com cd4511 para criar a alternância de cores, pois projeto é ligar primeiro os leds laranja, depois os vermelhos, depois os azul,depois todos ficarem ligados a mesmo tempo, depois alternando as cores. Podendo usar o botão para para alternar as ordem de iluminação do leds ou acordar o attiny85. 

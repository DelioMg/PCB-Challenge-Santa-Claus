# PCB-Challenge-Santa-Claus
Projeto de PCB desenvolvido para o Julialabs PCB Challange 2021, em que mostra as roupas que o Papai Noel usa em lugares muito quentes.

<p align="center"><img src="Imagens/santatop.png" width="600px" /></p>

### Funcionamento

A placa consiste em um attiny85 ligado ao um cd4511 para controlar 14 leds de tres cores:
- 4 leds laranja que vão da iluminação de fundo.
- 5 leds azul  que vai iluminar os símbolos da camisa.
- 4 leds vermelhos para iluminar a frente da PCB

Os leds escolhidos são para aplicações de baixo consumo devido a alimentação ser por uma bateria CR2030, pois os mesmo prometem entregar com 2mA a mesma luminosidade que um led comum consome a 20mA, em que eles forma ligados os pares em serie no cd4511 para aproveitando a tensões deles e utilizar menos saídas. 

Em que foi utilizado attiny85 com cd4511 para criar a alternância de cores, pois projeto é ligar primeiro os leds laranja, depois os vermelhos, depois os azul,depois todos ficarem ligados a mesmo tempo, depois alternando as cores. Podendo usar o botão para para alternar as ordem de iluminação do leds ou acordar o attiny85. 

## Imagens com os componetes 

<p align="center"><img src = "Imagens/santatop3d.jpg" width = "600">
<img src = "Imagens/santabuttom3d.jpg" width = "600"></p>


## Esquemático

![Schematics](Imagens/Schematics.jpg "Schematics")

## Lista de Compras

| Qtde| Item              | Descrição       |
| --- | ---               | ---             |
| 01  | [712-BAT-HLD-001](https://br.mouser.com/ProductDetail/712-BAT-HLD-001)    | Suportes de bateria     |
| 06  | [APHHS1005LSECK/J3-PF](https://br.mouser.com/ProductDetail/604-APHHS1005LSECKJ3)    | LED SMD Vermelho     |
| 04  | [SML-P11DTT86R](https://br.mouser.com/ProductDetail/755-SML-P11DTT86R)  | LED SMD Vermelho Laranja  |
| 05  | [APA2107LVBC/D](https://br.mouser.com/ProductDetail/604-APA2107LVBCD)     | LED SMD Azul Lateral  |
| 01  | [CD4511BPWR](https://br.mouser.com/ProductDetail/595-CD4511BPW)              | Multiplexador|
| 01  | [ATTINY85-20SUR](https://br.mouser.com/ProductDetail/556-ATTINY85-20SU)      | Microcontrolador |
| 01  | [TL3780AF100QG](https://br.mouser.com/ProductDetail/612-TL3780AF100QG)  | Interruptor tátil  |
| 01  | [CRCW04021K20JNTD](https://br.mouser.com/ProductDetail/80-C0805C105K4R7210)| Resistor 1.2k 0402  |
| 01  | [CRGCQ0402F10K](https://br.mouser.com/ProductDetail/279-CRGCQ0402F10K)         | Resistor 10k 0402 |
| 05  | [CR0402-FX-1501GLF](https://br.mouser.com/ProductDetail/652-CR0402FX-1501GLF)      | Resistor 1.5k 0402 |
| 01  | [CR1206-FX-1501ELF](https://br.mouser.com/ProductDetail/652-CR1206FX-1501ELF)       | Resistor 1.5k 1206 |



### Links
- [Carrinho de compras na Mouser](https://br.mouser.com/ProjectManager/ProjectDetail.aspx?AccessID=011ca5f7fb)
- [Projeto na PCBWay](https://www.pcbway.com/project/shareproject/Led_santa_claus_965c8ee7.html)

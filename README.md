# Eletronica - USP
Esse projeto da disciplina de Eletrônica da Universidade de São Paulo, com o apoio do professor Eduardo do Valle Simões  na disciplina SSC0180, foi desenvolvido com o objetivo de construir uma fonte de tensão ajustável que funciona com uma corrente contínua de 100mA.

## Componentes da fonte de tensão

* Transformador: Transforma a alta tensão da tomada em uma tensão mais baixa a ser utilizada na fonte de tensão. Em compensação, a corrente aumenta de modo inversamente proporcional à tensão

* Diodo: Corrigem a corrente alternada e deixam-a positiva.

* Capacitor: Armazena a carga durante os picos da corrente alternada, liberando corrente quando a tensão do capacitor é maior que a tensão da fonte.

* Diodo Zener: Conduz corrente somente quando a tensão estiver acima da maior estipulada

* Resistor: Reduzem o potencial elétrico

* Potenciômetro: varia a resistência de acordo com o usuário da fonte

* Transistor: Utilizado para limitar a passagem da corrente

 ## Funcionamento 
 
* Transformação:

Na transformação, os sinais elétricos da entrada, que possuem uma corrente alternada com uma tensão de 127V e uma frequência de 60Hz, são modificados pelo transformador, de modo que a tensão seja diminuída para aproximadamente 12V. No entanto, as outras características da onda permanecem inalteradas.

* Retificação:

Na retificação, os sinais elétricos da corrente alternada são convertidos em um sinal sempre positivo por meio de uma ponte de diodos. Essa conversão resulta na eliminação dos valores negativos de tensão. Graficamente, a retificação faz uma reflexão dos termos negativos da DDP em relação à abscissa.

* Filtragem:

Na filtragem, os sinais elétricos são convertidos em valores aproximadamente contínuos por meio de um capacitor. Esse capacitor é carregado brevemente durante os períodos de voltagem máxima e libera corrente nos momentos em que a voltagem de entrada diminui. Dessa forma, é criada uma simulação de uma saída de tensão contínua, embora apresente algumas imperfeições conhecidas como "ripple".

* Estabilização:

Na estabilização, os sinais elétricos previamente processados são submetidos a uma ação complementar entre o diodo Zener e o transistor, visando uma maior estabilização e linearização. Isso garante que a saída do sistema forneça uma tensão constante e fixa, mesmo diante de possíveis imperfeições das etapas anteriores ou interferências de ruídos causados por flutuações de corrente e temperatura. Por fim, é possível ajustar o valor de saída utilizando um potenciômetro, dentro da faixa de 3V a 12V especificada.


## Contas

_terminar_

## Tabela componentes eletrônicos

| Quantidade  | Componente | Especificações  | Valor em reais |
| ------------- | ------------- | ------------- | ------------- |
| 1  | Tranformador  | 12V | Utilizado de Simões  |
| 1 | Capacidor | 1000mF | 0,49  |
| 1  | Potenciômetro | 10k Ω linear | 6,79  |
| 3  | Resistores | 4.7k Ω  | 0,21  |
| 1  | Diodo Zenner | 1N5243 13V/0,5W  | 0,60  |
| 1 | Fusível de pico | 0,5A  | 1,07  |
| 1 | LED | 5mm  | 0,49  |
| 1 | Transistor | NPN - BC337  | 0,68 |
| 1 | Ponte retificadora | 2W  | 3,98  |
| 20 | Jumper macho-macho | 20 cm  | 13,52  |
| 1 | Protoboard | Pequena  | 19,79 |
| 1 | Plug AC | 10A  | 5,82  |
| 1 | Header | 2,4mm  | 3,88  |
|  |  |  | Total: R$ 57,32 |


## Falstad
Circuito de um transformador com ponte de diodo: https://tinyurl.com/2g7hx9yo

![alt text](https://github.com/A1RT0N/Eletr-nica/blob/main/2023-06-24_20-12.png?raw=true)

## Cicuito no Eagle

_inserir parte do Zuco_


## Resultado
_inserir vídeo/foto do resultado com a protoboard_

## Integrantes:
* Bruno Kazuya Yamato Sakji
* Douglas da Fontoura Pereyra
* Henrique Vilela Zucoloto
* Ayrton da Costa Ganem Filho

## Créditos
Queremos agradacer ao nosso grande mestre: Eduardo do Valle Simões


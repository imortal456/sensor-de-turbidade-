# sensor-de-turbidade-
documentaçao do projeto: sensor de turbidez da agua
nome do projeto:sensor de turbidez da agua

objetivo:
o objetivo principal desse projeto e medir a turbidez da agua usando um sensor e exibir as leituras. isso pode ser util para monitoramento
ambiental avaliaçao de qualidade da agua ou fins educacionais.

materiais:
1. MB102 Solderless breadboard: servira como area de prototipagem onde os componentes eletronicos (sensor, display, fios) serao conectados
sem a necessidade de solda. permite facil montagem e modificaçoes do circuito

2.Arduino Uno R3 DIP Board com cabo USB: Esta e a placa microcontroladora que sera o "cerebro" do projeto. Ela lera os dados do sensor de
turbidez,os processara e enviara comandos. para o display LCD. o cabo USB para programar o Arduino e fornecer ernegia

3. 16x2 LCD Display: este display sera usado para mostrar as leituras de turbidez em um formato de facil compreensao (em NTU - Unidades
nefelometrica de turbidade) "16x2" significa ela pode exibir 2 linhas de 16 caracteres cada.

4.Sensor de Turbidade da Agua: Este e o componente crucial que medira a turbidez da agua. geralmente, esses sensores funcionam emitindo o
um feixe de luz e medindo a quantidade de espalhada ou absorvida por particulas na agua.A saida e geralmente uma tensao analogica que
varia com turbidez.

como o projeto ira funcionar:

1.conexao do sensor e aquisiçao de dados:
        - O Sensor de turbidez da agua sera submerso na agua  cuja turbidez precisa ser medida.
        - O sensor sera conectado a um pino de entrada analogica no Arduino uno.
        - O Arduino lera continuamente a saida de tensao analogica do sensor de turbidez. Essa tensao sera proporcional ao nivel de turbidez.

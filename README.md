#Apresentação arduino-abajur-bluetooth
Não vou me aprofundar no tema de automação, simplesmente mostrarei que com alguns módulo e alguns linhas de código podemos controlar um abajur através do bluetooth.
Utilizarei Arduíno e alguns módulos adquiridos pela internet, todas as referências a modelos e data sheets estarão documentados.
De maneira simples podemos nos comunicar com outros aparelhos em nosso dia-a-dia, podemos programá-los para se adaptar a nossa rotina e até a realizarem tarefas para nós, delegar, delegar.
#Requisitos
- Placa Arduíno Uno R3 [site oficial](https://www.arduino.cc/en/Main/ArduinoBoardUno), [schematic](https://www.arduino.cc/en/uploads/Main/Arduino_Uno_Rev3-schematic.pdf), [schematic download](http://download.arduino.org/products/UNO/Arduino-UNO-Rev3e-SCH.pdf), [ATMEGA 328 datasheet](http://www.mouser.com/pdfdocs/Gravitech_ATMEGA328_datasheet.pdf)
- Módulo HC-06 FC-114 [datasheet](http://www.wavesen.com/mysys/db_picture/news3/201652094211101.pdf), [BLK-MD-BC04-B](http://www.bolutek.cn/Products_info.asp?id=278)
- Módulo rele de 1 canal [onde encontrar](http://eletronicos.mercadolivre.com.br/pecas-componentes-eletricos/modulo-rele-1-canal-5v)
- Bateria 5v e um conector para arduino
#Introdução
O funcionamento será simples, o celular envia um sinal e o Arduíno executa o procedimento para o sinal recebido, resultando na luz acesa ou apagada.
Você precisa parear e se conectar por bluetooth ao hardware e enviar um sinal. Por exemplo, ao enviar o sinal de ` acender luz ` o Arduíno aciona o relé para acender a lâmpada. E ao enviar um sinal de ` apagar luz ` o Arduíno aciona o relé para desligar a lâmpada.
#Desenvolvimento
Vou utilizar o Arduíno Uno R3 por questões práticas.
##Passos
1-Começamos fazendo a ligação do bluetooth ao Arduíno;
2-Depois ligamos o relé ao Arduino;
3-Criamos um código para testar;





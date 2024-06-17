# Formula-E
Nomes e RM.
Gabriel Frageri Dias RM-556830

Gustavo Teixeira RM-557876

Pedro Paulo Garcia Silva RM-554880 

Pedro Pawlik Ferrari RM-556968

TRABALHO -----------------------------------------------------------------------------------

Monitor de Qualidade do Ar com LCD
Este projeto utiliza um Arduino com um display LCD para simular e exibir diferentes níveis de qualidade do ar. Cada nível é representado por uma mensagem específica no LCD, e a simulação é feita através de um ciclo contínuo que varia a qualidade do ar de 0 a 5.

Componentes Utilizados:
Arduino (qualquer modelo compatível)
Display LCD 16x2
Potenciômetro para ajuste de contraste do LCD
Fios de conexão
Bibliotecas Necessárias:
LiquidCrystal.h - Esta biblioteca é usada para controlar displays LCD baseados no chip HD44780.
Instalação:
Conecte o display LCD ao Arduino conforme o seguinte esquema:
VSS (Pin 1): GND
VDD (Pin 2): 5V
VO (Pin 3): Conectado ao centro do potenciômetro para ajuste de contraste
RS (Pin 4): D12 no Arduino
RW (Pin 5): GND (modo de escrita)
E (Pin 6): D11 no Arduino
D4 (Pin 11): D5 no Arduino
D5 (Pin 12): D4 no Arduino
D6 (Pin 13): D3 no Arduino
D7 (Pin 14): D2 no Arduino
A (Pin 15): 5V (backlight positivo)
K (Pin 16): GND (backlight negativo)
Conecte o Arduino ao computador e carregue o código fornecido.
Funcionamento:
O Arduino simula diferentes níveis de qualidade do ar de 0 a 5.
A cada iteração, o nível é incrementado circularmente.
A mensagem correspondente a cada nível é exibida no display LCD de 16x2.

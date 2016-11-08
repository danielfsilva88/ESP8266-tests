# ESP8266-tests
Repository to build a spot with ESP8266

Links to help the project

Uma lista completa dos
comandos para comunicação com o módulo pode ser encontrada em
http://www.pridopia.co.uk/pi-doc/ESP8266ATCommandsSet.pdf

O programa “wifitest”
https://developer.mbed.org/users/fookies/code/wifitest/
permite a comunição entre o módulo e um terminal no PC, como o TeraTerm. Para a
comunicação com o módulo pelo TeraTerm é necessário habilitar o CR+LF para o
Receive e para o Transmit. Esta opção encontra - se em “Setup>Terminal”.

Siga o tutorial em
http://rancidbacon.com/files/kiwicon8/ESP8266_WiFi_Module_Quick_Start_Guide_v_1.0.4.pdf
para testar uma comunicação com um computador em uma mesma rede.
O cliente Telnet no Windows 8 e 10 deve ser instalado (“Feature” do Windows) em
“Programs and Features”.

Utilize o programa
https://developer.mbed.org/users/star297/code/ESP8266-configuaration-baudrate/
para configurar o módulo: coloque o nome da rede wireless (ssid) 
que será utilizada e sua senha (password); 
configure o baud do esp para 115200 tanto na linha 23 quanto na linha 52.

Utilize o programa
https://developer.mbed.org/users/star297/code/ESP8266-WEB-Mbed-Controller/
para criar um webserver um exemplo de página web que 
permite tanto receber informações do microcontrolador quanto atuar em suas
saídas. Este programa utiliza um sensor de temperatura, mas no exemplo ele não
precisa ser utilizado.

Tutorial WebServer ESP8266 + CodeWarrior
https://mcuoneclipse.com/2014/11/30/tutorial-web-server-with-the-esp8266-wifi-module/

Arquivos do tutorial
https://github.com/ErichStyger/mcuoneclipse/tree/master/Examples/KDS/FRDM-KL25Z/FRDM-KL25Z_ESP8266

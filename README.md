# Quarentino
 Projeto de robô auto balance, realizado durante a pandemia, que utiliza firmware de drone. Para outras informações acesse o post [Quaretino](https://omecatronico.com.br/blog/sr-quarentino/) no blog omecatronico.

### Fimware
- Firmware é o BalancingWii adaptado por mahowik.
- Link para o firmware [BalancingWii](https://github.com/mahowik/BalancingWii).
- É compatível com software MultiWiiConf.exe e via bluetooth com o EZ-GUI ground station.

### Eletrônica
- Placa customizada para Arduino nano v3, MPU6050 (GY-), stepstick A4988 (polulu), Motores nema17
- Esquema de ligações retirados da pagina do Firmware.
- Como não tenho módulo bluetooth, habilitei a porta D2 com o protocolo CPPM (controle de aeromodelos) 

### Estrutra
- Foram impressos os arquivos 3d no formato STL do site Thingiverse. Projeto Remotely controlled - Arduino Self balancing robot, do autor jjrobots.
- Link para os STL [Remotely controlled - Arduino Self balancing robot](https://www.thingiverse.com/thing:2306541)

OBS: na interface gráfica não apareceu a o valor de tensão… não verifiquei ainda o motivo.
OBS2: Como esse firmware não foi configurado para usar o braço do robô ainda não funciona, mas pela versatilidade do código será possível acrescentar o controle do braço futuramente.
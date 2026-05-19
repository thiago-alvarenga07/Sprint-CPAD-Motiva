# SIMA (Sistema Inteligente de Monitoramento Ambiental)
> Integrantes:
* Thiago Sobral de Alvarenga RM: 562695
* Pedro Miranda Campos Riato RM: 562117
* Israel Karacsony de Camargo Nunes RM: 563435
* Diego Antonio Silva Mendes RM: 565509
* Giovanni de Lela Anjos Costa RM: 563066
* Gabriel Hiro Nakamura RM: 562221
  
## 🤔Problema
Atualmente a CCR Motiva, possui um sistema totalmente manual para analisar o tamanho da grama dos acostamentos de suas rodovias, em que funcionários apenas visualisando anotam se o tamanho está ideal ou não, isso causa irregularidade e baixa precisão dos dados que são obtidos.

## 🎯Solução
Com essas informações tivemos a ideia de criar um aplicativo para os funcionários que serão responsáveis por realizar o corte da grama, para analisar os lugares que precisam do corte utilizaremos um sensor LiDAR que enviará os dados da grama para o aplicativo. No app o funcionário poderá gerenciar os sensores receber alertas de dispositivos que detectaram altura crítica da grama, gerenciar quantos trechos precisam de atenção.

## 🖥️Stack tecnológica
Linguagens de programação: JavaScript/React Native - desenvolvimento do app
Hardware: Sensor LiDAR, ESP32

## 🟢 Requisitos Funcionais
* **RF-001:** O sistema deve permitir o login de usuários com diferentes níveis de acesso (Admin e Operador).
* **RF-002:** O usuário deve conseguir alertar animais perigosos perto das vias.
* **RF-003:** O sistema deve enviar uma alerta ao usuário caso algum sensor detecte altura crítica da grama, ou risco de chuva forte

## 🟡 Requisitos Não Funcionais
* **RNF-001 (Usabilidade/Design):** A interface do usuário deve ser clara, para que qualquer funcionário consiga entender todas as funcionalidades
* **RNF-002 (Geolocalização):** A localização dos sensores deve ser precisa para evitar perda de tempo dos funcionários que realizaram o corte
* **RNF-003 (Segurança):** Os sensores devem ser instalados com travas antifurto, impossibilitando a remoção de pessoas não autorizadas.

## 📱Link do protótipo no Figma
https://www.figma.com/design/yXccF65DQpIKxfgpKkoyiy/Introdu%C3%A7%C3%A3o-ao-figma?node-id=0-1&t=yrCA3dPWtOYwJYLS-1

## 📷Prints do protótipo navegável
<img width="348" height="762" alt="image" src="https://github.com/user-attachments/assets/40ca6655-d83e-4f52-800d-1755c1a3d76d" />
<img width="348" height="762" alt="image" src="https://github.com/user-attachments/assets/6c23a0e2-5a22-4679-82b8-ca5057084884" />
<img width="348" height="762" alt="image" src="https://github.com/user-attachments/assets/da205d1e-4303-41f6-9b6d-a03f36558d79" />
<img width="348" height="761" alt="image" src="https://github.com/user-attachments/assets/2c2630e3-4d4c-4dd9-b5d3-39c262510650" />
<img width="350" height="762" alt="image" src="https://github.com/user-attachments/assets/fea1e9b0-e3e8-475c-a5fc-f30484ed9b59" />

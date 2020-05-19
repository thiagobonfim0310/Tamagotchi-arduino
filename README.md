  
 # Tamagochi 

 ### Esquema do projeto
 ***
![Esquematico](https://github.com/thiagobonfim0310/Tamagotchi-arduino/blob/master/Esquema%20Arduino%20Mega%20e%20Uno.jpg)

O uso de dois arduinos foi necessario devido, o processamento dos mesmos serem mono thread, usando um para processar a imagem exibida, e outro para processar o audio.

 ### Sobre o projeto 
 ***
 O projeto se trata de uma versão modificada de um brinquedo antigo chamado tamgochi, possui o mesmo principio de cuidar de um "bixinho de estimação", e em caso de descuido o bixinho morre e tudo reinicia.

 ### Componentes
***
 Os botões são reponsaveis pelas açoes dentro do jogo, o potenciomentro é responsavel pelo ajuste de brilho da tela.
 
 ### Funcionalidades
 ***
 O tamgochi possui 4 acões, sendo elas a escolha do personagem, alimentar, soneca e brincar onde o ultimo entra em uma joguinho.

**Escolha do personagem:** O jogo possui 3 personagens, a escolha de cada um se da pressionando o botão especifico, sendo cada personagem correspondente a um botão na ordem de cima para baixo sao os botões da esquerda para a direita.

**Alimentar:** É acionado apertando o primeiro botão da esqueda para a direita e a partir dai acontece uma animção.

**Soneca:** É acionado apertando o botão central e a partir dai a tela inverte as cores dando um tom negativo para representar a soneca e permanece por 10 segundos


**Brincar:** É acionado pelo ultimo botão da esquerda para a direita e entra em uma joguinho onde o usuario controla uma nave para desviar dos meteoros, a nave é controlada pelos botões das extremidades 


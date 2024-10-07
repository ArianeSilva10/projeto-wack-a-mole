# Projeto Whack-a-Mole em BeagleBone Black

<p style="text-align:center">
    <a href="#sobre">Sobre</a> • 
    <a href="#funcionalidades">Funcionalidades</a> • 
    <a href="#Estrutura-do-Projeto">Estrutura do Projeto</a> • 
    <a href="#Hardware-Utilizado">Hardware Utilizado</a>  •     
    <a href="#Colaboradores">Colaboradores</a> 
</p>

### Sobre
 Este é um jogo de Whack-a-Mole desenvolvido em C utilizando a BeagleBone Black. O jogo envolve LEDs, botões, um LCD para pontuação e um timer para controlar a velocidade de aparecimento dos "moles". À medida que o jogador acerta, o jogo aumenta a dificuldade, incrementando a velocidade.

### Funcionalidades

- Pontuação e Vidas: A pontuação aumenta a cada acerto, e o jogador tem um número limitado de vidas que diminui a cada erro.
- Controle de LEDs e Botões: LEDs representam as "moles" que precisam ser acertadas, e botões são usados para acertar o LED correspondente.
- Aumento de Dificuldade: A velocidade aumenta gradualmente para desafiar o jogador.
- Interrupções e Pooling: O projeto utiliza interrupções para detectar a pressão dos botões, bem como pooling em alguns casos.

###  Estrutura do Projeto <a id="Estrutura-do-Projeto"></a>

- gpio.h: Biblioteca para controle dos GPIOs.
- timer.c: Código para configurar e gerenciar os temporizadores.
- lcd.c: Código para exibir a pontuação no LCD.

### Hardware Utilizado <a id="Hardware-Utilizado"></a>

- BeagleBone Black: Controladora principal do projeto.
- LEDs e Botões: Utilizados para interatividade.
- Display LCD: Exibe a pontuação e o status do jogo.
![BeagleBone Black](https://i0.wp.com/makezine.com/wp-content/uploads/2013/04/beagleboneblack01.png?fit=1349%2C900&ssl=1)


### Colaboradores
- F. Ariane S. Silva
- Raissa Ívyna


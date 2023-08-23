# ![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white) **Arduino**

Espaço para desenvolvimento de orientações a respeito do uso da plataforma Arduino em projetos de Engenharia Mecânica.

## O que é o Arduino?
Arduino é uma pequena placa de circuito que tem um potencial gigantesco. Pode ser tanto hardware quanto software (NUSSEY, 2019). Em termos práticos, um Arduino é um pequeno computador que você pode programar para processar entradas e saídas entre o dispositivo e os componentes externos conectados a ele (McROBERTS, 2011).
A placa Arduino é um microcontrolador de placa única baseado em um processador denominado Atmel AVR com suporte de entrada e saída para sinais digitais e analógicos. A placa arduino UNO, por exemplo, é capaz de receber sinais digitais ou analógicos e processá-los. Para isso, a placa precisa ser programada previamente utilizando software próprio.

**Figura 1** - Placa de circuitos do Arduino Uno.

![image](https://github.com/LPATROCINIO1969/Arduino/assets/79651078/486fa97a-5af3-4019-bb10-cbbcbddc0450)

O Arduíno é uma plataforma de computação física ou **embarcada**, ou seja, é um sistema que pode interagir com seu ambiente por meio de hardware e software. Por exemplo, suponha uma sistema de iluminação formado por várias luminárias distribuídas em um ambiente. Pode-se utilizar o Arduino para acender essas luzes numa ordem específica ou aleatória, em intervalos regulares de tempo, tipo o que se faz em um pisca-pisca de Natal, ou ainda como resposta a estímulos externos, semelhante a um sistema de alarme. Para isso, o Arduino se liga fisicamente por meio de suas entradas e saídas lógicas ao circuito das luminárias. Internamente, ele irá armazenar e executar um software criado especificamente para controlar as luzes das luminárias (McROBERTS, 2011).

Obviamente, se você é o projetista/construtor de um sistema baseado no Arduíno, terá que fazer as ligações físicas e posteriormente desenvolver o software para tarefa específica a ser realizada pelo seu projeto. Porém, o aspecto interessante do Arduíno é sua facilidade para implementar tanto as ligações físicas em hardware, quanto para criar o programa de computador que irá controlar o sistema. Isto tornou essa plataforma muito popular entre os Makers de final de semana, estudantes de nível médio e superior, pois não é necessário conhecimento aprofundado de eletrônica digital para criar pequenos projetos em Arduíno. Além disso, muitas plataformas similares ao Arduíno, além de clones (Beduíno, Induíno, Microduíno, etc.), foram criadas e também podem ser usadas para o desenvolver projetos baseados na plataforma Arduíno.

## O que pode ser feito com Arduino?
O Arduíno permite criar uma infinidade de aplicações que vão desde o controle de múltiplos sensores e transdutores, inclusive registrando as medidas coletadas, até efetuar o acionamento/controle de dispositivos tais como motores e reles, e/ou dispositivos robóticos. A comunidade do Arduíno é bastante ativa e o tempo todo está criando novas aplicações para esta plataforma, conforme pode ser visto no [Site oficial do Arduino](https://www.arduino.cc/).

Nos links [built-in examples](https://docs.arduino.cc/built-in-examples/) e [libray-examples](https://docs.arduino.cc/library-examples/) podem ser encontrados vários exemplos de pequenas aplicações de Arduíno com esquemas detalhados de montagem da placa e código de programa no [Site oficial do Arduino](https://www.arduino.cc/).



## Orientações Gerais para um Projeto em Arduino

1. Antes de começar qualquer projeto em Arduíno você precisa de um **ambiente de programação do Arduíno** em seu computador. Neste ambiente você poderá desenvolver o programa de controle da placa. Para isso, há duas formas de proceder:
    - Se você tem conexão com a internet, pode **acessar** um ambiente de programação online disponível neste link: [online IDE Arduino](https://create.arduino.cc/editor)
    - Se você pretende trabalhar offline, pode instalar o software para desenvolvimento em seu computador, fazendo o **download** pelo link: [desktop IDE](https://www.arduino.cc/en/Main/Software#download)


## Projetos Utilizados em Aula

+ [Projeto 01: *TERMÔMETRO DIGITAL BASEADO EM ARDUINO*](https://github.com/LPATROCINIO1969/Arduino/blob/main/TermometroDigital_01.md)

## Sites de interesse
+ [Site oficial do Arduino](https://www.arduino.cc/)
+ [built-in examples](https://docs.arduino.cc/built-in-examples/) - lista de exemplos de aplicações básicas em Arduíno presentes na IDE do Arduíno
+ [libray-examples](https://docs.arduino.cc/library-examples/) - seleção de aplicações exemplo do Arduíno, utilizando bibliotecas específicas.

## Vídeos de interesse
+ [O que é Arduino, afinal de contas? #ManualMaker Aula 4, Vídeo 1](https://youtu.be/sv9dDtYnE1g?si=UeJtqoNw31OfbN2X)
+ [Use um Arduino sem ter Arduino! #ManualMaker Aula 5, Vídeo 1](https://youtu.be/CrHJj4OQ6Sw?si=q3hxL2asRdcQoa8f)
+ [Conheça os sensores do Arduino #ManualMaker Aula 6, Vídeo 1](https://youtu.be/vEdYjAbzrAE?si=lpzmEVB86Euq5Kdp)
+ [Como funciona uma protoboard #ManualMaker Aula 3, Vídeo 2](https://youtu.be/DfU6llvIMcM?si=z8TA3jHfJmQt875-)
+ [Como funciona um multímetro #ManualMaker Aula 2, Vídeo 2](https://youtu.be/1WIWrmc-rBk?si=YYHXf5jDlwjS0iMT)
+ [Para que servem os componentes eletrônicos? #ManualMaker Aula 3, Vídeo 1](https://youtu.be/C54Cp819Ebc?si=WC-CXoraHSysacQP)

## Referências
+ NUSSEY, J. **Arduino para Leigos**. Rio de Janeiro: Alta Books, 2019.
+ McROBERTS, M. **Arduino Básico**. São Paulo: Novatec Editora, 2011.
+ KARVINEN, Kimmo; KARVINEN, Tero. Primeiros passos com sensores: perceba o mundo usando eletrônica, arduino e raspberry pi. Novatec Editora, 2014.




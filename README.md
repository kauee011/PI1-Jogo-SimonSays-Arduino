
#PI I - Jogo Simon Says com Arduino

##Descrição do Projeto Este projeto foi desenvolvido como Projeto Integrador I (PI I) da FATEC Santo André. Consiste na implementação do clássico jogo "Simon Says" (Genius), utilizando o Arduino Uno para controle de LEDs e botões. O foco foi na aplicação de lógica sequencial e conceitos de eletrônica básica.

##Tecnologias e Componentes O projeto combina software e hardware para criar a interface do jogo:

Microcontrolador: Arduino Uno (para o controle de sequência).
Linguagem: C++ (utilizada na IDE do Arduino).
Componentes: LEDs (para o padrão visual), Botões/Chaves (para a entrada do usuário) e Buzzer (para feedback sonoro, se aplicável).
##Funcionamento O jogo gera uma sequência aleatória de luzes e sons, que o usuário deve repetir corretamente. O código C++ gerencia a lógica da sequência, a leitura das entradas do usuário e o feedback de acerto/erro.

Este projeto demonstra proficiência em lógica de programação e manipulação direta de I/O (Input/Output) de um microcontrolador.
##Estrutura do Repositório

SimonSays.ino: Contém o código C++ principal para o Arduino, incluindo a lógica de geração da sequência, leitura de botões e controle dos LEDs/Buzzer.

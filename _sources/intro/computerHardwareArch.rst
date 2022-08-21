Arquitetura de hardware de um computador
----------------------------------------
.. index::
    single: Hardware
    pair: Hardware; Arquitetura
    single: Programa
    single: Unidade central de processamento
    single: Memória principal
    single: Memória secundária
    single: Dispositivos de entrada e saída
    single: Conexão de rede

Antes de aprendermos a linguagem que utilizamos para instruir um computador,
nós precisamos aprender um pouco sobre como os computadores são construídos.
Se nós desmontarmos um computador ou telefone celular e olharmos o que ele
possui dentro, nós encontraríamos os seguintes componentes:


.. figure:: Figures/arch.svg
    :alt: Hardware Architecture


Uma definição simples para cada um desses componentes é a seguinte:


*
  A *Unidade central de processamento* (UCP ou CPU, do inglês Central
  Processing Unit) é a parte do computador que é obsecada em saber o
  próximo comando a ser executado. Se o seu computador é dito como 
  3,0 Gigahertz (GHz), isso significa que sua CPU perguntará qual é
  o próximo comando três bilhões de vezes por segundo. Você aprenderá 
  como falar rápido o suficiente para manter a CPU ocupada.

*
  A *memória principal* é utilizada para armazenar as informações que a CPU
  precisa imediatamente. Ela também é conhecida por RAM (de Random Access
  Memory ou Memória de Acesso Aleatório). A memória principal é quase tão
  rápida quanto a CPU, porém ela esquece as informações que ela armazenou
  assim que o computador for desligado. 

*
  A *memória secundária* também é utilizada para armazenar informações, mas
  ela é muito mais lenta que a memória principal. A vantagem dela é que ela
  pode armazenar informações mesmo quando o computador está desligado. Exemplos
  de memória secundária são os discos rígidos rotativos (HD), discos de estado
  sólido (SSD ou M.2) e os módulos de memória USB (pendrives).

*
  Os *dispositivos de entrada e saída* são as formas com que interagimos com
  o computador e vice-versa. Exemplos de dispositivos de entrada e saída são:
  tela do computador, teclado, mouse, microfone, caixa de som, touchpad.

*
  Atualmente, a maioria dos computadores possui também uma *conexão de rede*
  para obter dados de uma rede de computadores (como a Internet). Nós podemos
  pensar da rede como um local lento para armazenar e obter informações que
  nem sempre estão disponíveis. De certa forma, uma rede funciona na prática
  como uma *memória secundária* mais lenta e pouco confiável.

.. mchoice:: intro-hardware-mc-storage
    :practice: T
    :answer_a: Memória principal
    :answer_b: Memória secundária
    :answer_c: Unidade de processamento central
    :answer_d: Dispositivos de entrada e saída.
    :correct: b
    :feedback_a: Tente novamente. A informação armazenada na memória principal é apagada assim que o computador é desligado.
    :feedback_b: Correto! A memória secundária manterá informação mesmo sem energia.
    :feedback_c: Tente novamente. A CPU é quem faz a computação.
    :feedback_d: Tente novamente. Dispositivos de entrada e saída são outros tipos de hardware, sem relação com armazenamento de dados.

    Qual dos seguintes componentes manterá as informações armazenadas mesmo sem uma fonte de energia?



Embora seja função dos fabricantes de computador saber a maioria dos detalhes
de como esses componentes funcionam, é útil saber um pouco da terminologia
para que possamos trabalhar com essas diferentes partes quando escrevermos
nossos programas.

.. dragndrop:: intro-hardware-dnd-memory
    :practice: T
    :match_1: Memória principal|||Armazena informações rapidamente para a CPU; precisa de energia para manter os dados.
    :match_2: Memória secundária|||Armazena informaçẽos lentamente; pode manter as informações na ausência de energia.
    :match_3: Dispositivos de entrada e saída|||Componentes físicos que geralmente ficam fora do computador, que mostram informações ou capturam dados.
    :match_4: Conexão de rede|||Permite que informação seja armazenada em uma rede; muito lenta.
    :match_5: Unidade central de processamento|||Realiza efetivamente a computação e execução de programas no computador.

    Associe cada termo com a sua definição.



Como um programador, nosso trabalho é usar e orquestrar cada um desses
componentes para resolver os problemas que precisamos e analisar os dados
que obtemos da solução. Como um programador, você falará principalmente
com a CPU, dizendo o que ela deve fazer a seguir. Algumas vezes você
pedirá para a CPU usar a memória principal, a memória secundária, a rede
ou os dispositivos de entrada e saída.


.. figure:: Figures/arch2.svg
    :alt: Onde você está?


Você precisa ser a pessoa que responde à pergunta da CPU de "qual é o
próximo comando?". Todavia, seria muito desconfortável encolhê-lo para
uma altura de 14nm (ou menos!) e inserí-lo dentro do computador só para
você desse o comando três bilhões de vezes por segundo. Ao invés disso,
você escreverá os comandos previamente. Nós chamamos esses comandos
armazenados de *programa* e o ato de escrever esses comandos corretamente
nós chamamos de *programação*.


.. fillintheblank:: intro-hardware-fitb-program
    :practice: T

    Um grupo de comandos armazenados utilizado para direcionar a unidade central de processamento de seu computador é chamado de ________.

    - :[Pp]rograma: Um programa armazena das instruções que respondem a questão do "qual é o próximo comando?" de uma CPU.
      :[Pp]rogramação: Programação é o processo de criar e editar esses comandos.
      :.*: Tente novamente!
      

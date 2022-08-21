Blocos básicos de contrução de programas
----------------------------------------
.. index::
    single: Entrada
    single: Execução sequencial
    single: Saída
    single: Execução condicional
    single: Execução com repetição
    single: Reutilização

Nos próximos capítulos, aprenderemos mais sobre vocabulário, estrutura
das frases, estrutura dos parágrafos e estrutura de histórias escritas
em Python. Nós aprenderemos sobre as fantásticas capacidades do Python
e como utilizá-las para criar programas úteis.

Existem alguns conceitos e padrões básicos que nós utilizamos para
construir programas. Esses elementos não são utilizados apenas para
programas em Python, mas também para a maioria das linguagens de
programação, desde aquelas de baixo nível (próximo da linguagem de
máquina) até o nível mais alto (próximo da linguagem natural):

* entrada
    Obter dados do "mundo exterior". Isto pode consistir da leitura de
    dados de um arquivo ou de algum tipo de sensor, como um microfone
    ou GPS. Em nossos primeiros programas, nossa entrada será obtida
    do teclado, conforme os dados digitados pelo usuário.

* saída
    Mostrar os resultados do programa em uma tela, armazená-lo em um
    arquivo ou talvez enviá-lo para um dispositivo como uma caixa de
    som, permitindo tocar uma música ou falar um texto.

* execução sequencial
    Executar comandos um após o outro, na ordem com que eles estão
    no programa.

* execução condicional
    Verificar certas condições para então decidir entre executar ou
    pular uma sequência de comandos.

* execução com repetição
    Executar uma sequência de comandos repetidamente, geralmente com uma
    pequena variação quanto a valores considerados pelos comandos.

* reutilização
    Escrever uma sequência de comandos uma vez e dar um nome para ela,
    permitindo reutilizar essa sequência de comandos no seu programa
    conforme necessário e de forma mais fácil.

Parece muito simples para ser verdade e na verdade nunca foi tão simples.
É como se disesse que andar é simplemente "colocar um pé na frente do outro".
A "arte" de escrever um programa de computador é a combinação desses elementos
básicos por diversas vezes para produzir algo útil para o usuário.

O programa para contar palavras da seção anterior utiliza diretamente todos
esses padrões básicos, exceto por um.


.. fillintheblank:: intro-bb-fitb-pendrive-out
  :practice: T

  Quando escrevendo dados (por exemplo, músicas) para um módulo de memória USB (pendrive), o pendrive é um exemplo de ________ para um programa de computador.

  - :[Ee]ntrada: Não exatamente. O pendrive está sendo lido ou está sendo escrito pelo programa?
    :[Ss]aída: O aparelho de música mostrará os resultados escritos pelo programa quando o pendrive for reproduzido/tocado.
    :.*: Tente novamente.

.. fillintheblank:: intro-bb-fitb-pendrive-in
  :practice: T

  Quando lendo dados contidos em um pendrive, o pendrive é um exemplo de ________.

  - :[Ee]ntrada: O pendrive contém dados os quais o programa lê.
    :[Ss]aída: Não exatamente. O pendrive está sendo lido ou escrito pelo programa de computador?
    :.*: Tente novamente.

.. dragndrop:: intro-bb-dbd-terms
  :practice: T
  :match_1: Entrada|||Obtenção de dados de fora do computador.
  :match_2: Saída|||Apresentação ou produção de dados pelo programa.
  :match_3: Execução sequencial|||Execução de comandos um após o outro, na ordem em que eles são encontrados.
  :match_4: Execução condicional|||Verificação de certas condições para então executar ou pular uma sequência de comandos.
  :match_5: Execução com repetição|||Execução de uma sequência de comandos várias vezes, geralmente com alguma pequena variação.
  :match_6: Reutilização|||Escrita de uma sequência de comandos uma única vez, atribuindo-lhe um nome e então chamando esse grupo de instruções por esse nome, conforme necessário no programa.

  Associe cada padrão de construção com o que ele significa para um programa.

Conversando com o Python
------------------------
.. index::
    single: Modo interativo

Agora que nós temos uma palavra e uma frase simples que nós sabemos em
Python, nós precisamos aprender como começar uma conversa com Python para
testar nossas novas habilidades com esta linguagem.

Antes que você conversa com Python, você deve instalar o Python em seu
computador e aprender a iniciá-lo. Isso é muito detalhe para tratar aqui,
então eu sugiro que você consulta em `www.py4e.com <http://www.py4e.com>`_
onde temos instruções detalhadas de como configurar e iniciar o Python
em máquinas com sistemas MacOS e Windows. Em algum ponto, você chegará
a um terminal ou janela de comandos em que você digitará *python* e então
o interpretador Python iniciará a execução no modo interativo, aparecendo
algo como o que segue:

.. code-block:: python

   Python 3.5.1 (v3.5.1:37a07cee5969, Dec  6 2015, 01:54:25)
   [MSC v.1900 64 bit (AMD64)] on win32
   Type "help", "copyright", "credits" or "license" for more
   information.
   >>>


O ``>>>`` é a forma do interpretador Python pedir para você "qual é a próxima
coisa que você quer que eu faça?", indicando que ele está pronto para ter uma
conversa com você. Tudo que você precisa saber agora é falar a linguagem
Python.

.. fillintheblank:: intro-convo-fitb-prompt
  :practice: T

  Qual é o símbolo do interpretador Python que pede "qual é a próxima coisa que você quer que eu faça?"

  - :>>>: Correto! >>> é o prompt do interpretador Python.
    :.*: Tente novamente. Abra o seu interpretador Python com o comando "python" e veja com o que você é solicitado a interagir.


Digamos que você não sabe as palavras mais simples ou frases da linguagem
Python. Você pode desejar usar a famosa frase que astronautas utilizam
quando pousam em um planeta distante e tentam conversar com os nativos:

.. code-block:: python

   >>> Eu venho em paz, por favor leve-me ao seu líder
   File "<stdin>", line 1
     Eu venho em paz, por favor leve-me ao seu líder
          ^
   SyntaxError: invalid syntax
   >>>


Isto não está indo bem. A menos que você pense em algo rapidamente, os
habitantes do planeta podem atacá-lo e serví-lo de janta. Por sorte, você
trouxe uma cópia deste livro e você abre exatamente neste ponto do texto
e tenta novamente:


.. code-block:: python

   >>> print('Olá! Eu venho em paz')
   Olá! Eu venho em paz


Isto está parecendo muito melhor, então você tenta se comunicar um pouco mais:

.. code-block:: python

   >>> print('Você deve ser o deus lendário que veio do céu')
   Você deve ser o deus lendário que veio do céu
   >>> print('Nós estávamos esperando por você por todo esse tempo')
   Nós estávamos esperando por você por todo esse tempo
   >>> print('Nossa lenda diz que você deve ser muito saboroso com mostarda')
   Nossa lenda diz que você deve ser muito saborodo com mostarda
   >>> print 'Nós teremos um banquete hoje a menos que você diga
   File "<stdin>", line 1
     print 'Nós teremos um banquete hoje a menos que você diga'
                                                      ^
   SyntaxError: Missing parentheses in call to 'print'
   >>>


A conversa estava indo tão bem e então você fez um pequeno erro usando a linguagem
Python, podendo trazer tudo a perder novamente.

.. mchoice:: intro-convo-mc-print
  :practice: T
  :answer_a: vírgulas
  :answer_b: colchetes
  :answer_c: ponto e vírgula
  :answer_d: parênteses
  :correct: d
  :feedback_a: Qual é o símbolo necessário para completar o comando print?
  :feedback_b: Quais são os símbolos necessários ao redor do texto a ser impresso?
  :feedback_c: Tente novamente.
  :feedback_d: Correto! Parênteses são necessários ao redor do conteúdo a ser impresso pelo comando.

  O que está faltando no comando 'print'?

  ::

    print('Nós teremos um banquete hoje a menos que você diga')

Neste ponto, você percebe o quanto o Python é complexo, poderoso e muito exigente
(chato) quanto à sintaxe com que você deve ser comunicar com ele. Python *não* é
inteligente. De fato, você está tendo uma conversa consigo mesmo, mas com uma 
sintaxe adequada.

Nesse sentido, quando você usa o programa escrito por outra pessoa, a
conversa é entre você e algum outro programador (que escreveu o outro programa),
sendo o Python apenas um intermediário. Assim, Python é uma maneira com que
criadores de programas de computador expressam como a conversa deve proceder.
Após alguns capítulos de aprendizado, você será um desses programadores que
usam Python para conversar com os usuários de seu programa.

Antes de deixarmos para trás essa primeira conversa com o interpretador Python,
você deve aprender a maneira adequada de dizer "tchau" quando interagindo com
os habilidantes do Planeta Python:

.. code-block:: python

   >>> tchau
   Traceback (most recent call last):
   File "<stdin>", line 1, in <module>
   NameError: name 'tchau' is not defined
   >>> se você não se importa, eu preciso ir embora
   File "<stdin>", line 1
     se você não se importa, eu preciso ir embora
              ^
   SyntaxError: invalid syntax
   >>> quit()


Você perceberá que o erro é diferente para cada uma das tentativas. A maneira
correta de encerrar a conversa com o Python, quando no modo interativo do
interpretador, é usando o comando *quit()*. 


.. fillintheblank:: intro-convo-fitb-quit
  :practice: T

  O que você precisa digitar para sair do interpretador Python?

  - :quit(\(\))*: Correto!
    :.*: Tente novamente.

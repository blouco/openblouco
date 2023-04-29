.. _Papo:

Papo
====

Usaremos um webchat embedável direto nas páginas da :ref:`Rua`, que através dos
poderes web do KiwiIRC e da rede de IRC Libera.Chat permitirá que possamos falar
facilmente através de todas as páginas de forma acessível, combinando o Papo
com os outros :ref:`Elementos`.


IRC!!?!?!?
----------

O `mIRC <https://canaltech.com.br/curiosidades/10-anos-sem-brasnet-se-voce-usou-o-mirc-voce-esta-ficando-velho-97294/>`__, companheiro de Internet de muita gente nos anos 90 e 00, é apenas um
dos vários clientes / apps que permitem acessar as redes IRC, que continuam
bastante ativas para alguns públicos, como os desenvolvedores de software
livre, e continua sendo uma possibilidade fácil e universal de *chat*.


Rede Libera.Chat
----------------


Ao contrário do Whatsapp, Telegram, e tantos mensageiros que temos hoje em dia,
no IRC você pode escolher o programa que usa para se conectar e também o
servidor, uma vez que "IRC" é o *protocolo* (um grande combinado de vocabulário
e gramática pra computadores se entenderem sobre um assunto, aqui neste caso
salas de chat).

Utilizamos o `Libera.Chat <https://libera.chat/>`__, por conta de sua praticidade e gratuidade mas
principalmente por seu alinhamento com a comunidade de software livre -- o
:ref:`Blouco` no fim das contas é um grande algoritmo executado em aliança por
humanos e máquinas.


O Libera.Chat hospeda uma versão do KiwiIRC e torna muito fácil embutir um chat dentro da -- é o que estamos fazendo com as páginas da :ref:`Rua`! Ele pode ser acessado de forma independente por aqui:

https://web.libera.chat/

KiwiIRC
-------

A solução mais acessível para levar o IRC até o navegador, de forma prática e
bunita, é o KiwiIRC:

    KiwiIRC torna o Web IRC fácil. Um cliente IRC feito à mão do qual você pode
    desfrutar. Projetado para ser usado facilmente e livremente.

    https://kiwiirc.com/

Configurando e mantendo o canal
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Quando você se entra em um canal não registrado (será sempre nosso caso na criação de um Blouco), torna-se a operadora do canal ("Op"), que permite *kickar*, banir, e também tornar a pessoa administradora (ou *voice*, que permite que ela fale quando o canal é mutado).

Clicando no ícone de engrenagem ⚙️ no canto superior direito, é possível acessar todas as configurações numa interface simples.

Mudando e registrando o nick
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Por se tratar de uma rede bem grande e antiga, é muito possível que nicks simples já estejam registrados. Clicando no ícone de lápis ✏️ que aparece ao clicar em seu  *nick*, é possível mudá-lo.

Encontrando um que esteja disponível, registrá-lo só requer contatar `@NickServ` (o bot de registro) através do comando:

`/nickserv register SUA_SENHA SEU_EMAIL`

Seu *nick* já está registrado, e continuará por mais que um dia se você seguir o
e-mail de confirmação.



Exemplo de uso do KiwiIRC
^^^^^^^^^^^^^^^^^^^^^^^^^

Vídeo em inglês e com uma versão bem antiga, mas o processo é o mesmo.

.. raw:: html

    <iframe width="560" height="315" src="https://www.youtube.com/embed/x7g0IBLTFLQ" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Conectando externamente
-----------------------


.. image:: https://www.mirc.com/images/indexlogorbf.gif
    :align: center


Se você estiver no computador (pois no celular vai perder o foco da transmissão), pode usar qualquer outro cliente IRC para conectar-se, até o saudoso (mas não morto) `mIRC <https://www.mirc.com/>`__. Nossa recomendação para uma solução fácil, funcional e de código aberto é o `HexChat <https://hexchat.github.io/>`__.

.. image:: https://hexchat.readthedocs.io/en/latest/_images/channel_window.png
    :align: center
    :width: 600px


Uso avançado
------------

.. raw:: html

    <center><iframe width="560" height="315" src="https://www.youtube.com/embed/jcsku9R3v6U" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>


Bots
----

.. image:: /images/elementos/papo/meetbot.png
   :align: center
   :width: 600px

.. image:: /images/elementos/papo/meetbot2.png
   :align: center
   :width: 600px

Bots serão muito bem vindos para utilidades e também para algazarras. Por ser um protocolo bem consolidado e bastante antigo, existe uma variedade grande de pacotes e módulos prontos para implementar bots.

`Make A Retro Chatbot For IRC <https://hackernoon.com/make-a-retro-chatbot-for-irc-3eada517967>`__


BotyMcBotface
^^^^^^^^^^^^^



    BotyMcBotface (because what else can you name a bot, really?) is a simple
    IRC bot skeleton inspired by the tutorial at
    https://pythonspot.com/en/building-an-irc-bot. This skeleton doesn't really
    do anything; it was designed as an example of how to write a bot that
    others can build upon.

    https://github.com/enfors/botymcbotface




Sopel
^^^^^

    Sopel is a simple, easy-to-use, open-source IRC utility bot, written in
    Python. It’s designed to be easy to use, easy to run, and easy to extend.

    https://sopel.chat/

    Plugin commands

    This page contains a list of all commands from plugins within Sopel’s main
    plugins directory. If you have added plugins without rebuilding the
    documentation, or are using a secondary plugins directory, those plugins
    will not be shown here

    https://sopel.chat/usage/commands/

    meetbot.py - Sopel Meeting Logger Plugin

    https://github.com/sopel-irc/sopel/blob/master/sopel/modules/meetbot.py

MeetBot
^^^^^^^

    MeetBot is designed to assist in running meetings, taking notes, and so on.
    It is in pure python, as a plugin to supybot. However, there is a clear
    distinction between meeting-code and IRC-code, so it should be relatively
    easy to port to other bots. It is under the supybot license (3-clause BSD).

    https://wiki.debian.org/MeetBot/

Bots de cadeia de Markov - Texto gerado por computador
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Algo que é simples e pode ser bem divertido é colocar bots soltando frases de tempos em tempos baseadas em cadeias de Markov (como autocompletar do celular).

Aqui um exemplo de texto gerado por essa `ferramenta online
<https://projects.haykranen.nl/markov/demo/>`__ usando algumas letras de
marchinha:

.. image:: /images/elementos/papo/markov_marchinha.png
   :align: center
   :width: 400px

Programando diretamente é possível fazer o bot cuspir conteúdos mais elaborados, começando com uma determinada palavra por exemplo, ou alimentar ele usando o conteúdo já presente no chat. Também é possível fazer com que isso aconteça de tempos em tempos, ou acionado por um comando por mensagem.



Duas ferramentas para criar bots de Markov para o IRC facilmente:

**dagbot:**

    An IRC Markov Chain chatbot with a simple pluggable command system using
    Python 3.6. [...] Commands have a very simple interface which tell the bot
    what keywords are triggers & what class should handle said keywords.

    https://github.com/anirbanmu/dagbot


**markov-irc:**

    IRC bot with text generation based on Markov property. A Redis database is
    used to store words.

    https://github.com/miedzinski/markov-irc

CloudBot
^^^^^^^^

    CloudBot is a simple, fast, expandable open-source Python IRC Bot!

https://github.com/TotallyNotRobots/CloudBot

Limnoria
^^^^^^^^

    Limnoria is a robust (it doesn’t crash), user friendly (it’s easy to
    configure) and programmer friendly (plugins are extremely easy to write)
    Python IRC bot. It aims to be an adequate replacement for most existing IRC
    bots. It includes a very flexible and powerful ACL system for controlling
    access to commands, as well as more than 60 builtin plugins providing
    around 400 actual commands.

https://docs.limnoria.net/

    collection of plugins for Limnoria.

https://github.com/jlu5/SupyPlugins/

A curated list of awesome IRC resources.
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

https://github.com/davisonio/awesome-irc



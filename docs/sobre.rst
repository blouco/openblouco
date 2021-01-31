.. _Sobre o OpenBlouco:

Sobre o OpenBlouco
==================

O OpenBlouco é um ~padrão~ aberto e colaborativo para a construção de *bloucos*, uma adaptação livre das dinâmicas de blocos de carnaval autônomos para as ruas da Web.

O `primeiro Blouco`_ sairá no dia 14 de fevereiro, que seria o Carnaval
2021 se não fosse a bact... as restrições sociais da COVID-19.

.. _primeiro Blouco: https://blouco.neocities.org


Queremos chegar em uma colagem de plataformas Web que permita criar uma
coalizão descentralizada de foliãs guiadas através da música e da visão
através das ruas da Web e da Internet -- espaços públicos de
socialização pouco explorados em tempos de jardins murados das redes
sociais.

Estamos aqui nesta documentação criando componentes para materializar todos os seguintes ambientes e seus protocolos internos de uso e passagem, com as prioridades de ter baixo custo (serviços oferecidos gratuitamente, ferramentas livres e de código aberto, etc), fácil implementação e resiliência quanto ao uso por pessoas novatas, bêbadas ou mucho lokas de forma geral.


Ambientes e funções
-------------------

.. image:: https://github.com/blouco/openblouco/blob/main/docs/images/chave.png?raw=true
  :align: center

.. image:: https://github.com/blouco/openblouco/blob/main/docs/diagramas/geral.png?raw=true
  :align: center


A **Rua**, ambiente de chegada das **Incautas** no blouco, é uma página web
simples HTML+CSS que consolide, através de *embeds*, um documento de
boas vindas, a transmissão do Trio e o acesso ao Papo.

O **Papo** é o ambiente público de *chat*, onde as **Foliãs** podem assumir qualquer
apelido e interagir ao som do Trio. Ele é o ambiente inicial de contato
do público externo com quem está dentro do blouco, e é habitado pelas
Incautas que se aproximam do blouco pela Rua e pelas **Cordões**, que
fazem a contenção da Rua e o intermédio entre ela e os outros
ambientes do blouco.

O **Trio**, um *streaming* de áudio e vídeo, é gerida coletivamente pelas **Artistas** em um
ambiente próprio, e transmite a música e o vídeo guias do blouco.

O **Desfile**, uma sala de videoconferência, congrega as **Passistas** quem quer dançar junto
e ficar o mais coladinho possível virtualmente.

O **Estandarte**, um documento colaborativo, é o ponto de partida e
focal de organização do blouco; é empunhado por **Porta-estandartes**.


Mapa em Rede
------------

Grafo sendo desenvolvido no `GraphCommons`_:

.. _GraphCommons: https://graphcommons.com

.. raw:: html

    <iframe src="https://graphcommons.com/graphs/6ce351e8-4382-46b7-abdc-5a247c13d9f7/embed" frameborder="0" style="overflow:hidden;border:1px solid #DDDDDD;width:1px;min-width:100%;height:400px;min-height:400px;" width="100%" height="400" allowfullscreen></iframe>


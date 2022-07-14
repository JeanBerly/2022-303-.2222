<!-- # 2022-303-NomeASerDefinido -->

<h1 align="center">🚧Essa ainda não é a versão final do jogo🚧</h1>

<p align="center"> Equipe: Amanda Bueno, Gabriel Moreira, Jean Berly, Ulisses Rosa </p>

# Considerações Iniciais
- Essa é a disposição inicial dos objetos, basicamente, um protótipo de como será a interface dos menus após a criação das artes.
- A acessibilidade visual (filtros de cor, legendas e alterações nos textos, etc) será aplicada depois da criação de um protótipo jogável
- A navegação entre os botões pode ser feita através do teclado, usando as setinhas
- O idioma poderá ser alterado entre inglês e português
- Somente as funcionalidades de navegação entre menus foi implementada ainda

# Menu Principal

## Tela inicial:
Primeiramente, temos o "Main Menu" que possui 3 botões clicáveis
- Jogar -> Inicia o jogo
	- Ao iniciar o jogo, o jogador poderá escolher a dificuldade do jogo
- Opções -> Abre o Menu de Opções (detalhado no próximo tópico)
- Sair -> Fecha o jogo

<p align="center"><img src="https://user-images.githubusercontent.com/68441010/171026477-d74a5c43-ef1e-40c3-95e8-87abc3eb21ab.jpg" alt="Menu principal do jogo, no qual o título se destaca na parte superior da imagem e as opções abaixo"</p>

## Tela de opções:
- No menu das opções temos as configurações de jogabilidade e acessiblidade.
- Alternando entre as opções (usando o teclado ou o mouse), conseguimos alterar as opções do submenu lateral

### Audio
- Aqui é possivel alterar o volume geral do jogo
- Também será possivel alterar o volume durante o jogo, através de um menu de pause
	
<p align="center"><img src="https://user-images.githubusercontent.com/68441010/171026536-7fceda2e-30bf-4a25-bdad-1fe406d9ce10.jpg" alt="Menu das opções aberto com a opção de áudio selecionada, onde é possível alterar o volume geral"></p>


### Acessibilidade
- Aqui será possivel ativar e configurar as opções de acessibilidade:
	- Opções de texto (legenda, tamanho da fonte da legenda)
	- Filtros de Imagem (Protanopia, Deuteranopia, Tritanopia)
	- |*Possibilidade*| Audiodescrição e narração em LIBRAS

<p align="center"><img src="https://user-images.githubusercontent.com/68441010/171026625-eecdf1c7-a9fc-4dd7-a46d-f261de6203e1.jpg" alt="Menu das opções aberto com a opção de Acessibilidade selecionada, onde é possível ativar/desativar as seguintes opções: Legenda, Filtro de Imagem, Audiodescrição e Libras."></p>

### Idioma
- Aqui, o jogador pode alterar o idioma dos textos do jogo entre inglês e português

<p align="center"><img src="https://user-images.githubusercontent.com/68441010/171027556-7b06de34-f383-4ba0-b813-234f01d1b66e.jpg" alt="Menu das opções aberto com a opção de Idioma selecionada, onde é possível escolher entre Inglês e Português"></p>

### Maze Generator
- Tendo em vista que a gameplay do nosso jogo se passa em um labirinto, para evitar o repetitivo trabalho de criação manual dos tilemaps de mapas, implementamos um gerador de labirintos. Dessa forma, conseguimos fazer com que o jogador tenha uma experiência diferente a cada vez que ele joga 2222.

<p align="center"><img src="https://user-images.githubusercontent.com/81490716/179044603-70a6a2d8-ebfe-4a68-a1f4-e0eeaf1ace64.png" alt="Inspector do gerador de labirintos"></p>

- Os sprites e o tile map da parede e do chão são passados como parâmetros no inspector do gerador de labirintos. Com isso conseguimos providenciar uma customização para o layout do labirinto.

<p align="center"><img src="https://user-images.githubusercontent.com/81490716/179046968-6ff37f2a-8bf5-446b-8ff6-104014d03a54.png" alt="Tela da Unity"></p>






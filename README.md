# Chovendo-Paradas
<h2>Compilado no terminal do linux com o comando:</h2> 
g++ -o programa main.c personagem.c parada.c menu.c textura.c -lSOIL -lglut -lGLU -lGL -lm
ou
make

<h2>Executando:</h2>
make run
ou
./programa

<h2>instalação:</h2>
	sudo apt-get install build-essential
	sudo apt-get install freeglut3-dev
	sudo apt-get install libglew1.6-dev
	sudo apt-get install libsfml-dev
	sudo apt-get install libsoil-dev
ou
make install

<h2>Como jogar:</h2>
desvie das estrelas ninjas que caem
use as setas -> e <- para movimentar de um lado para o outro
p para pausar/voltar
r para reiniciar
esc para encerar
use o mause para selecionar os botoes play, negativo, afirmativo


<h2>Bonus:</h2>
uso do mouse
varias telas
animaçoes de dano e morte
audio para diferentes situacoes do jogo (tela inicial, tela de game over, jogo, tela win, colisao)

<h2>Bibliotecas:</h2>
grew
freeglut
soil
sfml

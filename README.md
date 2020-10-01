# Quiz-game :question:
Um jogo de perguntas com problemas matemáticos feito em GO.

# Como executar :eyes:
 - Tenha o go instalado na sua máquina, você pode baixa-lo [aqui](https://golang.org/dl/)
 - Tenha o git instalado na sua máquina, você pode baixa-lo [aqui](https://git-scm.com/downloads)
 - Navegue pelo terminal até a pasta onde deseja salvar o projeto e execute o comando ``` git clone https://github.com/dougmendes/quiz-game.git```
 - Execute o comando ```go build . && quiz-game.exe``` - WINDOWS ou ```go build . && ./quiz-game``` - LINUX


# Regras :memo:
 - São apresentados problemas matemáticos simples onde é esperada uma resposta.
 - Existe um tempo de resposta para o questionario.
 - Caso não seja informado qual o tempo disponível para responder todo o questionario será aplicado o padrão de 30 segundos.
 
# Opções :gear:
  - O jogador pode adicionar mais problemas matemáticos no arquivo problem.csv.
  - O tempo de resposta pode ser passado na chamada do programa(em segundos) com a tag -limit, exemplo: ```go build . && quiz-game.exe -limit=1```

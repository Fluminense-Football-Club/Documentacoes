# Documentacoes
Instalação do ambiente python, para as API funcionarem:

Passos para inicializar o ambiente de desenvolvimento de nossa API "SGF"

1- Tenha o python e o pip instalado.


2- Crie um ambiente virtual Python com o comando (no terminal do python) "python -m venv Nome_Ambiente" ou "python3 -m venv Nome_Ambiente"


3- Ative o ambiente virtual criado com o "selecionar interpretador python" dentro de sua IDE (VScode) ou executando o arquivo "..\Nome_Ambiente\Scripts\activate.bat" (Windows) 
ou  "source Nome_Ambiente/bin/activate" (Linux)


4- Após encontrar a pasta criada no passo anterior, clone o repositório "SGF" dentro do ambiente 
no caminho ..\Nome_Ambiente\Lib\site-packages\ 
Comando no gitbash: "git clone -b API --recursive https://github.com/Fluminense-Football-Club/sgf.git SGF"


//Para atualizar as bibliotecas

5- Dentro da pasta, no vscode "..\Nome_Ambiente\Lib\site-packages\SGF" criada no passo anterior execute o comando "pip install -r Requirements.txt". 
Tenha certeza que o ambiente virtual esteja ativado.


Após estes passos todo o ambiente já está configurado, basta utilizar as aplicações e bibliotecas nele.
Obs: Caso instale uma nova lib/dependencia, por favor, não esqueça de utilizar o "pip freeze >../Requirements.txt" e efetuar commit para atualizar o repositório.


1)
https://github.com/BrotherPlayerBR/my_first_steps.git

2)
mkdir my_first_steps
cd my_first_steps
git init
git add README.md
git commit -m Vinculando Repositório
git branch -M main
git remote add origin https://github.com/BrotherPlayerBR/my_first_steps.git
git push -u origin main

3)
touch ola_mundo.txt
git add ola_mundo.txt
git commit -m 'Criando Primeiro Arquivo'
git push
echo Arquivo ola_mundo.txt para Exercicio 3 >> ola_mundo.txt
git add ola_mundo.txt
git commit -m Adicionando Texto ao Arquivo txt
git push

4)
echo > .gitignore
git add .gitignore
git commit -m 'Criando o Arquivo .gitignore'
git push
echo IGNORADO! >> serei_ignorado.txt
echo serei_ignorado.txt >> .gitignore
git add .
git commit -m Ignorando Arquivo serei_ignorado.txt
git push

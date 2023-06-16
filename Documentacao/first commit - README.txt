Quando o repositório for novo e não tiver nenhum arquivo dentro use esses códigos abaixo para criar um arquivo README.md só pra ter algo dentro do repositório. Pois assim da pra clona-lo e realiar os commits.


.echo "# reposit-rio_estudo_git" >> README.md

.git init

.git add README.md

.git commit -m "first commit"

.git branch -M main

.git remote add origin [link SSH do repositório sem aspas] ex.:git@github.com:lucas-carmona/reposit-rio_estudo_git.git 

.git push -u origin main


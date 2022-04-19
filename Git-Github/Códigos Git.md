# Códigos Git
### Lista para relembrar
&nbsp;

&nbsp;
- **`git init`** para inicializar o repositório

- **`git add nome do arquivo`** coloca o arquivo na área de stagging

&nbsp;
*`git add .`* para todos os arquivos

- **`git commit -m "nome do commit"`** da o commit (nome/nota da alteração para criar uma versão) no repositório

- **`git remote add origin link do repositório`** conecta o commit do repositório local (referenciado como **`origin`** por padrão) com o Github

- **`git push -u origin main`** joga os arquivos do conteudo da branch **`main`** para a nuvem do Github

&nbsp;
***`main`*** ou ***`master`*** são nomes padrão da branch principal, para a alteração de outras branchs deve-se utilizar o nome da mesma no lugar

- **`git checkout -b "nome da branch"`** alterna o foco do GitBash para uma branch ou cria uma nova branch caso não tenha nenhuma com o nome utilizado e ja posiciona o foco nela

- **`git branch -M "nome da branch"`** altera o nome da branch em foco (inclusive da principal)

- **`git merge nome da branch`** pega as alterações da branch escolhida e aplica elas na branch em foco

- **`git clone link do repositório`** copia um repositório para sua maquina
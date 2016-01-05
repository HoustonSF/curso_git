# curso_git
##testes Houston S. Fernandes
1. Para começar este trabalho, inicialmente criei o diretório testes_git:

*$ mkdir testes_git *
*$ cd testes_git *

2. Foi iniciado o controle de versão neste diretório com o comando **$ git init**

3. Foram criados os arquivos:
  *arq1.txt
  *arq2.txt
  *arq3.txt

4. Foi consultado o *status* dos arquivos utilizando o comando: **$ git status**, sendo informado que os arquivos estavam como *'untracked'*, não relacionados.

5. Foram adicionados os arquivos no repositório com o comando **$ git add .**, que adiciona todos os arquivos do diretório atual, passando seus status para *staged*, prontos para serem commitados.

6. Então, para passá-los para o repositório utilizei o comando **$ git commit -m'messagem informando o commit'**.

Também foram realizados, testes alterando arquivos e verificando a mudança do estado para *modified*, precisando este arquivo ser novamente *adicionado* ao repositório, através de *commit* para fazer parte da próxima versão.
 
7. Para passar o trabalho para o **GITHUB**, foram realizadas as seguintes etapas:
  1. Criar conta: [GITHUB](github.com) 
  2. Criar Repositório
  3. Acessar repositorio [curso_git](https://github.com/houstonfernandes/curso_git)
  4. Adicionar (informar) repositorio remoto ao meu git local: **$ git remote add origin https://github.com/houstonfernandes/curso_git** 
  5. Enviar branch local para diretorio remoto: **$ git push origin master**, sendo origin o *alias* do branch remoto e *master* o meu branch local. 



Consegui fazer este texto formatado seguindo:[utilizando MarkDowns](https://help.github.com/articles/markdown-basics/)
UHUUU!!! agora vou testar no github!!!

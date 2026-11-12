# ProjetGit
Abra o terminal do Windows PowerShell, cada uma das instruções para configurar o repositório e registrar suas alterações:

PowerShell
1. Crie e acesse a pasta do projeto:
mkdir atividade-git && cd atividade-git

2. Gere o arquivo de texto inicial:
touch readme.txt

3. Defina suas credenciais globais de identificação no Git:
git config --global user.name "Caio"
git config --global user.email " caio.santos.amaral@escola.pr.gov.br "

4. Inicie o versionamento na pasta atual:
git init

5. Insira o texto dentro do arquivo criado:
echo "Atividade de Git realizada por Caio" > readme.txt

6. Prepare o arquivo e salve a primeira versão no histórico:
git add readme.txt
git commit -m "Primeiro commit"

7. Para registrar a alteração posterior no arquivo (adicione novamente à área de preparação e finalize com a nova mensagem de registro):
git add readme.txt
git commit -m "Primeiro commit: criando e modificando arquivo"

pwd   : Mostra o caminho absoluto aonde vc está
touch : Cria o arquivo
ls    : Lista todos os arquivos do diretório
ll    : Alias para ls -l
df    : Mostra a quantidade de espaço usada no disco rígido
df -h : mostra os valores em quantidade de "leitura humana"
cd    : Acessa uma determinada pasta (diretório)
cd .. : Volta um diretório
cd ~  : Vai para o seu home
mkdir : Cria um diretório
rm    : Remove um arquivo
rm -r : Remover pastas arquivos
cat   : Imprimi um arquivo na tela
vim   : Abre o editor (precione insert para entrarno modo de edição, depois ctrl+C para sair do modo de inserção e :x para salvar e sair, para salvar somente :w para sair sem salvar :q!)
clear : Limpa o terminal (atalho Ctrl+L)
exit  : Fecha o terminal (atalho Ctrl+D)

--> Clonar um repositório:
git clone https://<SEU_USUÁRIO_DO_GIT>@bitbucket.org/wellinton_pedroso/treinamento.git

--> Adionar as mudanças ao Index:
git add .

--> Verifica o status das mudanças:
git status

--> Commit:
git commit -m "<COLOQUE_AQUI_UMA_BOA_MENSAGEM_E_QUE_FAÇA_SENTIDO>"

--> Envia as mudanças para o repositório remoto:
git push origin master

--> Abrir a interface grafica:
gitk

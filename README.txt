Inicializar repositório:
git init — cria um novo repositório Git no diretório atual.

Adicionar arquivos ao stage:
git add . — adiciona todos os arquivos modificados para o próximo commit.

Configurar email global (corrigido):
git config --global user.email "dorneleseder1234@gmail.com" — define o email do usuário para todos os repositórios.

Configurar nome global:
git config --global user.name "Eder013" — define o nome do usuário para commits.

Adicionar repositório remoto:
git remote add origin https://github.com/Eder013/teste.git — adiciona a URL do repositório remoto chamado origin.

Fazer commit com mensagem:
git commit -m "meu primeiro commit" — cria um commit com a mensagem especificada.

Renomear branch para main:
git branch -M main — muda o nome da branch atual para "main".

Enviar branch para o GitHub:
git push -u origin main — faz push da branch main para o remoto e configura rastreamento; pode pedir autenticação via navegador.
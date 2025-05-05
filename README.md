# teste-mkdocs

* Testes com MkDocs e Deploy com GitHub Actions

# Configuração

* No arquivo **deploy.yml** 
* Crie o projeto com o comando: **mkdocs new meu-projeto-teste**
* Instale os plugins com o comando: **pip install mkdocs-meta-descriptions-plugin** e **pip install mkdocs-material**
* Rode o projeto com o comando: **mkdocs serve**, roda no servidor local o projeto
* Rodar o comando: **mkdocs gh-deploy** para atualizar a documentação direta na branch **gh-pages**, esse comando faz um commit direto nesta branch assim disparando o Actions para a implementação das mudanças.

# Observações

* Ao realizar o push para o repositório automaticamente será feito a sincronização do GitHub Actions e feito o deploy no Pages, rodando o primeiro Actions que seria a criação do build e ao final o último Actions onde faz a publicação da pasta site no Pages.
* Não commitar a pasta **site** na **main**, essa pasta deve ficar somente na branch **gh-pages**
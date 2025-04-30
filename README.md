# teste-mkdocs

* Testes com MkDocs e Deploy com GitHub Actions

# Configuração

* Crie o projeto com o comando: **mkdocs new meu-projeto-teste**
* Instale os plugins com o comando: **pip install mkdocs-meta-descriptions-plugin** e **pip install mkdocs-material**
* Rode o projeto com o comando: **mkdocs serve**

# Observações

* Sempre que for realizar alguma alteração no projeto recomendamos que execute o comando: **mkdocs build**, esse comando cria os arquivos finais dentro da pasta **site**
* Ao realizar o push para o repositório automaticamente será feito a sincronização do GitHub Actions e feito o deploy no Pages
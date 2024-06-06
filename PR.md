# ENGWEB2024-Recurso

### Preparar o Dataset

Para começar foi necessário a preparação dos dados. Para isso observei o ficheiro `dataset.json` e apercebi-me que este tinha alguns erros.
Para começar, faltava-lhe o delimitador para fechar o json. Adicionei este manualmente.

De seguida apercebi-me que existiam certos _arrays_ que se encontravam como _strings_, para isso utilizei o script `prepare.py` para os transformar. Neste script aproveitei e troquei o uso de bookId pelo _id para a base de dados.

### Queries

Tendo o dataset preparado dei setup de um pequeno docker-compose para poder rodar a base de dados e testar as queries através do `mongosh`.

Estas podem ser encontradas no ficheiro `queries.txt`

### Ex1

Para o `GET  /books/:id` decidi utilizar o _id (bookId) do dataset.

### Ex2


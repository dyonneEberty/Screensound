
# Desafio


Implementei uma aplicação para armazenar dados de meus artistas e músicas preferidos em um banco de dados relacional, podendo buscar informações por artistas e consultar dados sobre os mesmos através de integração com a API do ChatGPT.

- Criei uma classe Artista, com os dados para representar o mesmo
- Desenvolvi também uma classe específica para representar as músicas
- Para o artista, implementei um enum para definir o tipo do artista, por exemplo: solo, dupla ou banda.
- Criei o projeto através do site do Spring Initializr, onde já adicionei as dependências do Spring Data JPA e do PostgreSQL.
- Desenvolvi uma classe principal com o menu, com as opções desejadas, como: cadastrar artista, cadastrar música, pesquisar música por artistas, etc.
- Lembrei de estender o CommandLineRunner na classe do Spring, sobrescrevendo o método run para chamar o menu criado.


## 🔨 Objetivos do projeto

- Meu objetivo no projeto foi praticar a modelagem de classes e relacionamentos utilizando o Spring Data JPA
- Foi importante para mim descrever e implementar corretamente a relação entre Artista e Música, visto que um artista pode estar associado a mais de uma música.
- Eu garanti que uma música só fosse salva no banco de dados se o Artista tivesse sido previamente cadastrado.
- Pratiquei derived queries e JPQL para verificar se o artista já estava cadastrado e buscar músicas por um determinado artista.
- Integrei a API do ChatGPT para buscar informações sobre um determinado artista.


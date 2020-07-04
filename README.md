# :rocket: Web Spring Boot

Este projeto foi desenvolvido durante o aulão disponibilizado pelo canal do youtube [devSuperior](https://www.youtube.com/channel/UC3twHmWQwtqEO7u-gB_2f7g).

## :pencil: Objetivos:

- Criar um simples projeto Java web no Spring Boot e Maven;
- Introdução prática a injeção de dependência no Spring Boot;
- Introdução prática a REST / web services;
- Introdução prática ao Spring Data JPA com banco H2;

## :pushpin: Passos

- Criar projeto Maven usando Spring Initializr e importar no STS

- Criar a entidade Category

- Criar CategoryResource

- Criar CategoryRepository

- Implementar CommandLineRunner para instanciar categorias no startup da aplicação. Usar o mecanismo de _injeção de dependência_ do Spring Boot para obter uma instância de CategoryRepository.

- Acrescentar entidade Product ao projeto

- Acrescentar as dependências Maven de Spring Data JPA e banco H2

- Acrescentar as configurações do H2 em application.properties

- Fazer os mapeamentos objeto-relacional

- Retirar os ID's das instâncias em CommandLineRunner (deixar como null)

- Trocar o código dos repositories: usar JpaRepository<Entity, ID>




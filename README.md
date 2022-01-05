# Especialista Spring REST

## 1 - Introdução

## [2 - Spring e Injeção de Dependências](/2.Spring-e-Injecao-de-Dependencias.md)

<details>
  <summary>Visualizar tópicos</summary>	

  - Spring Initializr

  - Spring Boot DevTools

  - Injeção pode acontecer

    - Pelo construtor
	
    - @Component
	
    - @Configuration + @Bean
	
    - @Autowired: no construtor, no setter ou atributo

      - A dependência pode ser opcional: permite realizar tratamento para quando não existir a dependência

  - Ambiguidade de beans
  
    - Desambiguação
	
      - Utilizando múltiplos beans
	  
      - Definindo o bean prioritário com @Primary
	  
      - @Qualifier para qualificar o @Component e indicar qual bean deve ser injetado
	  
      - Com anotação customizada: um @Qualifier customizado

  - Spring Profiles
  
    - Definindo comportamentos com @Profile("")
	
	- Selecionar ambiente pelo application.properties (um ou mais) OU parâmetro na IDE

  - Métodos de callback: ciclo de vida, @PostConstruct, @PreDestroy

  - Observer: publicar, consumir eventos

  - Propriedades

    - Properties file (application.properties, yml)
	
    - Variáveis ambiente do sistema operacional
	
    - Parâmetros por linha de comando
	
    - Propriedades customizadas com @Value
	
    - Propriedades com @ConfigurationProperties

  - Ativando Spring Profile

    - Via application.properties
	
    - Através de parâmetro na IDE
	
    - Por linha de comando
	
    - Por variável de ambiente
	
</details>	

## [3 - Introdução ao JPA e Hibernate](/3.Introducao-ao-JPA-e-Hibernate.md)

<details>
  <summary>Visualizar tópicos</summary>	

  - 3.1. Instalar MySQL Server e MySQL Workbench    
	
  - 3.2. O que é JPA e Hibernate?  	
  
  - 3.3. Adicionando JPA e configurando o Data Source
		
  - 3.4. Mapeando entidades com JPA
	
  - 3.5. Criando as tabelas do banco a partir das entidades
		
  - 3.6. Mapeando o id da entidade para autoincremento
  
  - 3.7. Importando dados de teste com import.sql
	  
  - 3.8. Consultando objetos do banco de dados
  
  - 3.9. Adicionando um objeto no banco de dados

  - 3.10. Buscando um objeto pelo id no banco de dados

  - 3.11. Atualizando um objeto no banco de dados
	  
  - 3.12. Excluindo um objeto do banco de dados
	  
  - 3.13. Conhecendo o padrão Aggregate do DDD   
	
  - 3.14. Conhecendo e implementando o padrão Repository
	
  - 3.15. Conhecendo e usando o Lombok
	
  - 3.16. Desafio: Lombok e repositório de restaurantes
	  
  - 3.17. Mapeando relacionamento com @ManyToOne
	  
  - 3.18. A anotação @JoinColumn	
	
  - 3.19. Propriedade nullable de @Column e @JoinColumn
	
  - 3.20. Desafio: mapeando entidades
	
</details>	
	
## [4 - REST com Spring](/4.rest-com-spring.md)

<details>
  <summary>Visualizar tópicos</summary>	
	
  - 4.1. O que é REST?
  
  - 4.2. Conhecendo as constraints do REST
  
  - 4.3. Diferença entre REST e RESTful
  
  - 4.4. Desenvolvedores de REST APIs puristas e pragmáticos

  - 4.5. Conhecendo o protocolo HTTP
  
  - 4.6. Usando o protocolo HTTP
  
  - 4.7. Instalando e testando o Postman
  
  - 4.8. Entendendo o que são Recursos REST
  
  - 4.9. Identificando recursos REST
  
  - 4.10. Modelando e requisitando um Collection Resource com GET
  
  - 4.11. Desafio: collection resource de estados
  
  - 4.12. Representações de recursos e content negotiation
  
  - 4.13. Implementando content negotiation para retornar JSON ou XML
  
  - 4.14. Consultando Singleton Resource com GET e @PathVariable

  - 4.15. Customizando as representações XML e JSON com @JsonIgnore, @JsonProperty e @JsonRootName
  
  - 4.16. Customizando a representação em XML com Wrapper e anotações do Jackson

  - 4.17. Conhecendo os métodos HTTP

  - 4.18. Conhecendo os códigos de status HTTP

  - 4.19. Definindo o status da resposta HTTP com @ResponseStatus

  - 4.20. Manipulando a resposta HTTP com ResponseEntity

  - 4.21. Corrigindo o Status HTTP para resource inexistente

  - 4.22. Status HTTP para collection resource vazia: qual usar?

  - 4.23. Modelando e implementando a inclusão de recursos com POST

  - 4.24. Negociando o media type do payload do POST com Content-Type

  - 4.25. Modelando e implementando a atualização de recursos com PUT

  - 4.26. Modelando e implementando a exclusão de recursos com DELETE

  - 4.27. Implementando a camada de domain services (e a importância da linguagem ubíqua)
  
  - 4.28. Refatorando a exclusão de cozinhas para usar domain services

  - 4.29. Desafio: modelando e implementando a consulta de recursos de restaurantes

  - 4.30. Modelando e implementando a inclusão de recursos de restaurantes

  - 4.31. Desafio: Modelando e implementando a atualização de recursos de restaurantes

  - 4.32. Desafio: implementando serviços REST de cidades e estados

  - 4.33. Analisando solução para atualização parcial de recursos com PATCH	
	
  - 4.34. Finalizando a atualização parcial com a API de Reflections do Spring
	
  - 4.35. Introdução ao Modelo de Maturidade de Richardson (RMM)

  - 4.36. Conhecendo o nível 0 do RMM

  - 4.37. Conhecendo o nível 1 do RMM

  - 4.38. Conhecendo o nível 2 do RMM

  - 4.39. Conhecendo o nível 3 do RMM
		
</details>
	
## [5 - Super poderes do Spring Data JPA](/5.super-poderes-do-spring-data-jpa.md)

<details>
  <summary>Visualizar tópicos</summary>	
	
  - 5.1. Implementando consultas JPQL em repositórios

  - 5.2. Conhecendo o projeto Spring Data JPA (SDJ)

  - 5.3. Criando um repositório com Spring Data JPA (SDJ)

  - 5.4. Refatorando o código do projeto para usar o repositório do SDJ

  - 5.5. Desafio: refatorando todos os repositórios para usar SDJ
	
  - 5.6. Criando consultas com query methods

  - 5.7. Usando as keywords para definir critérios de query methods

  - 5.8. Conhecendo os prefixos de query methods

  - 5.9. Usando queries JPQL customizadas com @Query

  - 5.10. Externalizando consultas JPQL para um arquivo XML


</details>	



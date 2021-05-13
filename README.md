# Especialista Spring REST

## 1 - Introdução

## [2 - Spring e Injeção de Dependências](/2.Spring-e-Injecao-de-Dependencias.md)

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
	

## [3 - Introdução ao JPA e Hibernate](/3.Introducao-ao-JPA-e-Hibernate.md)

  - 3.1 Instalar MySQL Server e MySQL Workbench    
	
  - 3.2 O que é JPA e Hibernate?  	
  
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
	
## [4 - REST com Spring](/4.rest-com-spring.md)

  - 4.1 O que é REST?
  
  - 4.2. Conhecendo as constraints do REST
  
  - 4.3. Diferença entre REST e RESTful
  
  - 4.4. Desenvolvedores de REST APIs puristas e pragmáticos

  - 4.5. Conhecendo o protocolo HTTP
  
  - 4.6. Usando o protocolo HTTP
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
	

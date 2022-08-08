# GrupoA Educação - Full Stack Web Developer

* Executando os projetos
````
	Back-end:
	 - cd api
	 - yarn install
	 - yarn typeorm migration:run (necessário executar as migrations)
	 - yarn dev

	Front-end:
	 - cd fe
	 - yarn install
	 - yarn serve
````

* Decisão da arquitetura utilizada
````
	Back-end:
	 - Desenvolvido em Node.js, está presente conceitos referentes à arquitetura limpa, como camada de entidades, serviços (casos de uso) e S.O.L.I.D.

	Front-end:
	 - Utilizou-se Vue.js, seguindo o padrão sugerido pela documentação.
````

* Lista de bibliotecas de terceiros utilizadas
````
	Back-end:
		- celebrate: validação de dados da request
		- class-transformer: 
		- typeorm: ORM utilizado para conexão com o banco de dados
		- reflect-metadata: facilidade para trabalhar com alguns conceitos utilizados no projeto

	Front-end:
		- axios: realizar requests para a API
		- vue-router: gerenciamento das rotas
		- vuex: gerenciamento de estado

	Demais bibliotecas não citadas aqui foram necessárias por necessidades comum ou por estarem instaladas, mas não serem usadas.
````

* O que você melhoraria se tivesse mais tempo
````
	Back-end:
		- Documentação total do projeto
		- Testes com mais "testes", indo além do coverage dos services

	Front-end:
		- Melhoraria os métodos para fazer as requests. Acredito que se explorasse mais, conseguiria deixar isso mais estruturado, removendo da camada do vuex. Apesar de ter resolvido o problema, particularmente, não gostei do método utilizado.
		- Adicionar testes, para deixar tanto back, quanto front, com cobertura total.
		- Acredito que o visual poderia ser mais agradável, acabei deixando passar alguns detalhes do Vuetify.
````

* Quais requisitos obrigatórios que não foram entregues
````
	Acredito que todos os requisitos foram cumpridos.
````

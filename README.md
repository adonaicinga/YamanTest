Automação Shoestock	
Nome(s):	Adonai Marques	
Data:	08/03/2021	
Escopo:	Automação site shoestock	
Premissa:	Testes automatizados	
		
Critérios de Aceite Ágeis  - BDD	
CT01 - Validar carrinho	Status
Dado	que entrar no site “  https:// www.shoestock.com.br”	(Passou)
E	Realizar Busca	(Passou)
Quando	Incluir produto no carrinho	(Passou)
Então	validar produto no carrinho	(Passo)

Tecnologias:
BDD: Cucumber
Linguagem: Java

Ferramentas:
Eclipse IDE for Java EE Developers
Postman
 

Execução:
Teste Web – Eclipse IDE

Package base = Classe com métodos WebDriver
Package elementos = Classe com elementos da pagina
Package runner = Classe onde o teste deve ser executado
Package steps = Classe com passos de teste
src/test/resources/bdd.feature = Arquivo cucumber com casos de testes

Teste API – Postman

Importar o arquivo "teste Api" no postman
codigos de validação na aba tests
 


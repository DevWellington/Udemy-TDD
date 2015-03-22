# Udemy-TDD
Projetos e Anotações do curso: TDD Para Bons Programadores PHP, apresentado pela escola Udemy.

##Aula 1 - Introdução ao curso
Test-Driven Development

Objetivo:

- Criar um codigo limpo e que funcione.

Problemas para alterar o código é um sinal de um mal codigo.

Codigo limpo que funciona é uma meta valisa por várias razoes:

- É uma forma previsível de desenvolver.
- Dá a voce uma change de aprender todas as liçoes que o codigo tem para ensinar.
- Melhora a vida dos usuarios de seu software.
- Permite que seus colegas de equipe contem com você, e você com eles.
- É bom escrevê-lo;

##Aula 2 - Por que?

Por que testar?

- Entender como funciona
- POde ser utilizado como parte da documentação.
- Treinamento do funcionamento do software;
- Facilitam a manutençao do código;
- Segurança para evolução do código;
- Verificar o bug;
- Garantir o funcionamento;

Nos desenvolvemos o software para os usuarios, então nosso dever é garantir a satisfação dos mesmos.

##Aula 3 - Tipos de Teste

O que representa cada tipo de teste.;

Você testar e não saber que tipo de teste voce esta fazendo
voce pode estar fazendo a coisa certa, mas de maneira
errada.

Pode estar com a ferramenta certa nas mãos, mas só terá
bons resultados se souber como utilizá-la;

O aprendizado deve ser formado pela teoria e pela prática.

####Níveis de Acesso 

- Caixa Branca 
	- Conhece e faz uso de testes de funcionamento **interno** 
	do software;
	
- Caixa Preta
	- Considera apenas a parte **externa** do software.
	- O Teste é realizado sob perspecitiva do usuário;
	- Testes de **Entrada** e **Saída**

####Tipos de Teste

- Manual:
	- Feito passo a passo por uma pessoa

- Automatizado
	- Realizado pelo computador.

##Aula 04 - Tipos de Teste Manual

Teste manual é dividido em:

- Testes em desenvolvimento (Testa enquanto desenvolve)
- Com script (equipe de testadores - Passso a Passo (Manual))
- Exploratório (Em busca de um erro)


Passível de erros:
- Testes em desenvolvimento
- Com script

Aceito:
- Exploratório 

##Aula 05 - Tipos de Teste Automatizado

- De unidade (Unit Test) - Caixa Branca
	- Unidade é uma pequena porçaõ do código
- De intergração (Integration Test) - Caixa Branca ou Preta
	- Visa testar a integração do software;
- De sistema (System Test) - Caixa Preta
	- Testa as funcionalidades do sistema;

	
Testes de Unidade:
Garantir cada unidade do código, de forma isolada;
É código testando código;

- Esta unidade pode ser:

	- Um método;
	- Uma classe;
	- Um módulo;

- Testes de Integração:

	- Banco de Dados;
	- API;
	- Gateway de pagamento;
	- Arquivos;
	
- Testes de Sistema:

	- Teste funcional;
	- De aceitação (User Acceptance Testing / Quality Assurance)
		- Testa os fluxos do sistema;
	- De interface gráfica;
		- Campos de texto, botões, menus, etc;
	- De stress;
		- Situações extremas de uso;
	- Fuzzing Test
		- Entradas diferentes (resultados inesperados)
	- Monkey Test
		- Semelhante ao teste manual exploratório;
		
##Questions:

1. Teste de unidade é um:

	R.: Teste caixa branca. Teste de unidade acessa cada classe e método do código, sendo obviamente um teste caixa branca.
			
2. Qual opção abaixo não é um teste de integração?

	R.: Teste de um método de validar de CPF. Teste de um método sem integração é um teste de unidade

3. O teste de sistema substitui um teste de unidade, pois já engloba todo o sistema.

	R.: Falso
	
4. O testador de uma empresa criou um roteiro com os testes que devem ser feitos no sistema, para que ele e os outros testadores pudessem executar sempre os mesmos passos. Qual o nome deste tipo de teste?

	R.: Teste manual com script. O roteiro nada mais é que um script de teste, e é um teste manual, pois é feito por pessoas
	
5. O teste de unidade pode testar somente um método de uma classe.

	R.: Verdadeiro
	
















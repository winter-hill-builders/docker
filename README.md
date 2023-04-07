# Requisitos do sistema

## Controle de Acesso

Deve exigir login e senha para acessar o sistema. Para a primeira entrega, será considerado apenas uma empresa.

No futuro, deve separar os acessos às informações de acordo com os times. Usuários da empresa X só acessam informações da sua própria empresa. 

No futuro, cobrança por cartão

## Deck

Deve gerar 5 listas de materiais ao final do orçamento para impressão (arquivo pdf). As 5 listas correspondem as seguintes abas da planilha:

* Galvanized
* PT Frame Material
* PT Finish OU PVC White Finish
* Board
* Rail

Deve mostrar a aba da planilha General Estimate


# Arquitetura 

## Banco de dados 

MongoDB
* Flexibilidade de nao precisar definir todos os campos. 
* Já nasceu preparado pra nuvem e clusterização. 
* Apresenta as características ACID para transação em um mesmo documento. 
* Estudar tecnologia nova, trabalhar com JSON/dicionário ao invés de SQL. 
* O wQuote é uma aplicação pequena. Logo, qualquer banco de dados praticamente resolve suas necessidades. 
* Tenha em mente que um PostgreSQL se encaixa perfeitamente a este caso. 
# Semana 01 - alura Challenges

Nessa primeira semana as tasks no Trello continham:
* as orientações iniciais;
* direcionamento para as bases de dados;
* regras de negócio para desenvolvimento dos indicadores.

## Propósito

A gestão do departamento de Logística necessita acompanhar alguns indicadores para que esteja em contato com a real situação e possa não apenas manter o padrão de trabalho, mas que melhore sua performance e tenha informações valiosas em mãos para tomada de decisão baseada em dados.

## Bases de Dados

É fundamental que o analista de BI conheça a(s) base(s) de dados que será(ão) utilizada(s) a fim de que consiga extrair ao máximo uma informação com valor agregado.

Para isso foram usadas quatro bases de dados:
* Estoque
* Pedidos
* Produtos
* Veículos

### A fundo nas bases de dados

A seguir irei detalhar todas as variáveis que cada base de dados contém e entre parênteses o formato que essa variável foi classificada no Power Query)

#### Base de Estoque
* ID Produto (Texto)
* Data atualização (Data)
* Quantidade (Número inteiro)

#### Base de Pedidos
* ID Pediddo (Texto)
* ID Produto (Texto)
* ID Veículo (Texto)
* Quantidade (Número inteiro)
* Status do pedido (Texto)
* Data da compra (Data)
* Data de entrega (Data)
* Data previsão (Data)
* Latitude (Latitude)
* Longitude (Longitude)
* UF da entrega (Texto)
* Status da Entrega (Texto) _variável criada_

#### Base de Produtos
* categoria_produto (Texto)
* preço (Número decimal fixo)
* ID Produto (Texto) _variável criada_
* Descrição do Produto (Texto) _variável criada_

#### Base de Veículos
* ID veículos (Texto)
* Tipo (Texto)
* Status (Texto)
* ID Veículo (Texto) _variável criada_

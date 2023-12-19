receba


Linguagem de programação central do projeto, utilizada para implementar toda a lógica e funcionalidades.
GUI Swing:

Biblioteca gráfica empregada na construção da interface gráfica do usuário. Responsável pela criação de elementos visuais, como botões e tabelas.
PostgreSQL:

Sistema de banco de dados utilizado para armazenar e gerenciar informações persistentes do sistema.
Estrutura do Projeto:
O código-fonte está organizado em diferentes pacotes, cada um com uma função específica:

Gerenciamento.Control: Contém classes responsáveis pelo controle e lógica de negócios do sistema.
Gerenciamento.Connection: Classes para interação com o banco de dados PostgreSQL.
Gerenciamento.Model: Classes de modelo representando as entidades do sistema.
Gerenciamento.View: Classes relacionadas à interface gráfica do usuário.
Manual de Uso:

Configuração do Banco de Dados:

Antes de executar o sistema, é necessário configurar corretamente o banco de dados PostgreSQL. As informações de conexão podem ser ajustadas no arquivo ConnectionFactory.java no pacote Gerenciamento.Connection.
Compilação e Execução:

Para compilar e executar o projeto, é necessário ter um ambiente de desenvolvimento Java configurado. Pode ser feito através de uma IDE Java, como Eclipse, ou por comandos no terminal.
Funcionalidades do Sistema:

Clientes:
Cadastro de Cliente: Adição de um novo cliente com CPF, nome completo e idade.
Atualização de Cliente: Modificação de informações de um cliente existente.
Exclusão de Cliente: Remoção de um cliente do sistema.
Estoque:
Cadastro de Produto: Adição de um novo produto no estoque com nome, preço e quantidade.
Atualização de Produto: Modificação de informações de um produto existente.
Exclusão de Produto: Remoção de um produto do estoque.
Atualização de Quantidade: Modificação da quantidade de um produto no estoque.
Vendas:
Registro de Venda: Adição de uma venda, incluindo cliente, valor, data e quantidade de produtos.

CONCLUSÃO: Para mim e o Luisao foi em desafio em tanto, gostariamos de usar só if else e JOptionPane, porem nao ia ficar legal kkkkk
pegamos inspiraçoes e dicas do GPT, porem tinhamos que integram as coisas do banco de dados, pensamos bastante, e conseguimos entregar isso.


BY: Roger Biagioni & Luis Barbosa
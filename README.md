# trabalho-final-ppi
Trabalho final da disciplina de programação para internet.

ALUNOS: PEDRO CAMPOS MIRANDA, ADILIO CARVALHO FERREIRA FILHO

TURMA: TDS 3



REQUISITOS FUNCIONAIS


1) O sistema deve permitir login de dois tipos de usuários: administrador e usuário comum (aluno).
2) O sistema deve validar o CPF e senha no momento do login.
3) O sistema deve controlar o nível de acesso, exibindo telas e funções diferentes para administradores e usuários comuns.
4) O sistema deve permitir o cadastro de novos usuários com os seguintes dados: id, nome de usuário, CPF, login e senha.
5) O sistema deve permitir à administradora editar e excluir usuários.

6) O sistema deve permitir à administradora cadastrar produtos com os campos: id, nome e descrição.
7) O sistema deve permitir listar, editar e excluir produtos cadastrados.
8) O sistema deve permitir à administradora registrar um pedido no momento em que o aluno retira o produto.

9) O pedido deve conter: id, descrição (produto e quantidade), valor total, data de criação e data de modificação.

10) O sistema deve descontar automaticamente o valor do pedido do saldo disponível do aluno.

11) O sistema deve atualizar o histórico de compras do aluno após cada pedido.

12) O sistema deve manter o registro financeiro dos alunos com os campos: id, nome, curso, CPF, nome do responsável e valor atual (saldo disponível).

13) O sistema deve permitir registrar recargas de crédito (entradas) vinculadas ao CPF do aluno.

14) As recargas devem incluir: id, id_financas, valor de entrada, responsável pelo pagamento, data de criação e modificação.

15) O sistema deve permitir registrar saídas referentes aos descontos das compras realizadas, com: id, id_financas, valor de saída, data de criação e modificação.

16) O aluno poderá visualizar seu saldo atual e seu histórico de compras.

17) O histórico do pedido deve exibir: nome do produto, data da compra e valor gasto.

18) O sistema deve permitir à administradora gerar relatórios de vendas em um dado período.

19) O relatório deve apresentar o total de vendas e os pedidos realizados dentro do intervalo informado.

20) Todas as informações devem ser salvas em um banco de dados MySQL.

Requisitos Não Funcionais

1) O sistema deve ser desenvolvido utilizando HTML, CSS, JavaScript, Node.js e MySQL.


2) A interface deve ser simples e intuitiva, adequada ao uso da cantina.


3) As telas devem estar organizadas e acessíveis para computadores e celulares.


4) As senhas dos usuários devem ser armazenadas de forma segura no banco de dados.


5) O sistema deve diferenciar os acessos de administradores e usuários comuns.


6) O sistema deve responder rapidamente às operações de cadastro, atualização e consultas.


7) O sistema deve garantir que as transações financeiras (entradas e saídas) sejam registradas corretamente.


8) O código deve ser organizado e comentado, facilitando futuras alterações.

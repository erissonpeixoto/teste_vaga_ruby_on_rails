# Teste para Programador Ruby on Rails - Intersol
## Sistema de controle Bancário com Ruby on Rails.

**Versão do Ruby: Minímo na 2.3**

**Versão do Rails: Mínimo na 5.0**

**Banco de Dados: Postgresql**

PRAZO PARA ENVIO
----------------
01/06/2020


INSTRUÇÕES
----------------
O objetivo do teste é criar um pequeno sistema de controle de conta bancária.

1- Deve ser possível logar no sistema usuando um nome de usuário ou e-mail juntamente com uma senha;

2- O sistema deve conter os seguintes modelos;

  * Usuários (login, senha)
  
  * Agências Bancárias (Número da Agência(string), Endereço(text))
  
  * Contas Bancárias (Agência Bancária(belongs_to), Número da Conta(string), Limite(decimal))
  
  * Movimentações da Conta (Conta Bancária(belongs_to), Data da Movimentação(date), Valor(decimal), Tipo de Movimentação(enum -> saque, Depósito, estorno, transferência), Usuário(belongs_to))
  
  obs.: todos os campos são obrigatórios e devem ter telas para possibilitar o cadastro a edição e a exclusão.


3- Deve ser possível registrar depósitos, saques, estornos e transferências entre contas;
   obs.: para realizar transferências entre contas, O modelo de Movimentações da Conta precisa ter dois belongs_to Conta        Bancária origem e destino.

4- Não deve ser possível excluir uma movimentação bancária;

5- Deve ser possível obter o saldo de uma conta bancária (deve aparecer nas views);

6- Uma movimentação não pode ser registrada se ultrapassar o limite da conta;

7- UPDATED: Fazer um fork ou mesmo um projeto novo e enviar o link do mesmo (para evitarmos que alguém copie o código do outro)

**Itens não obrigatórios mas que contarão como diferenciais:**
  
  * Para login e autenticação do sistema, usar a gem devise;
  
  * Usar Bootstrap ou Material Design nas views;
  
  * Usar frameworks javascript para melhorar a interação do usuário com os cadastros que deve realizar;
  
  * Utilizar testes, Rspec preferencialmente ou outro;
  
  * Publicar no Heroku.

Dúvidas entrar em contato por e-mail. Grato.


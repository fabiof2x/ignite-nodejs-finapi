## FinAPI - Financeira

API desenvolvida no Módulo I do curso de Node.js do Ignite.

---

### Como rodar o Projeto
```bash
    # Clonar o repositório
    $ git clone https://github.com/fabiof2x/ignite-nodejs-finapi
    # Entrar no diretório
    $ cd ignite-nodejs-finapi
    # Instalar as dependências
    $ yarn install
    # Iniciar o projeto
    $ yarn dev
```

---

### Tecnologias

- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com)

---

### Requisitos

- [x] Deve ser possível criar uma conta
- [x] Deve ser possível buscar o extrato bancário do cliente
- [x] Deve ser possível realizar um depósito
- [x] Deve ser possível realizar um saque
- [x] Deve ser possível buscar o extrato bancário do cliente por data
- [ ] Deve ser possível atualizar dados da conta do cliente
- [ ] Deve ser possível obter dados da conta do cliente
- [ ] Deve ser possível deletar uma conta
- [ ] Deve ser possível retornar o balanço

---

### Regras de negócio

- [x] Não deve ser possível cadastrar uma conta com CPF já existente
- [x] Não deve ser possível buscar extrato em uma conta não existente
- [x] Não deve ser possível fazer depósito em uma conta não existente
- [x] Não deve ser possível fazer saque em uma conta não existente
- [x] Não deve ser possível fazer saque quando o saldo for insuficiente
- [ ] Não deve ser possível excluir uma conta não existente
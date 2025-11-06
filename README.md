# APP

Suporte App

## RFs (requisitos funcionais)

- [ ] Deve ser possível se cadastrar;
- [ ] Deve ser possível se autenticar;
- [ ] Deve ser possível obter o perfil de usuário logado;
- [ ] Deve ser possível o usuário obter seu histórico de tickets;
- [ ] Deve ser possível o usuário abrir ticket;
- [ ] Deve ser possível o usuário acompanhar o ticket em aberto;

## RNs (Regras de negócio)

  - [ ] O usuário não deve pode se cadastrar com um e-mail duplicado;
  - [ ] O usuário não pode apagar um ticket aberto;
  - [ ] O usuário não pode alterar o status do ticket;

## RNFs (Requisitos não-funcionais)

- [ ] A senha do usuário precisa estar criptografado;
- [ ] Os dados da aplicação precisam estar persistidos em um banco PostgreSQL;
- [ ] Todas as listas de dados precisam estar paginadas com 20 itens por página;
- [ ] O usuário deve ser identificado por um JWT (JSON Web Token);


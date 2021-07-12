# NLW Valoriza


## Regras
- Cadastro de usuário
    - [X] Não é permitido cadastrar mais de um usuário com o mesmo email;
    - [X] Não é permitido cadastrar usuário sem email;
- Cadastro de TAG
    - Não é permitido cadastrar mais de uma tag com o mesmo nome;
    - Não é permitido cadastrar tag sem nome;
    - Não é permitido o cadastro por usuários que não sejam admin.
- Cadastro de elogios
    - Não é permitido um usuário cadastrar um elogio para si;
    - Não é permitido cadastrar elogios para usuários inválidos;
    - O usuário precisa estar autenticado na aplicação.

- Server -> (  controller  ) -> SERVICE -> Repositories -> BD

controller: funciona como request e response
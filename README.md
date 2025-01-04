# RF

- [x] O usuário deve poder criar uma nova transação;
- [x] O usuário deve poder obter um resumo da sua conta;
- [x] O usuário deve poder listar todas as transações que já ocorreram;
- [x] O usuário deve poder visualizar uma transação única;

# RN

- [x] A transação pode ser do tipo crédito que somará ao valor total, ou débito que subtrairá;
- [ ] Deve ser possível identificarmos o usuário entre as requisições;
- [ ] O usuário só pode visualizar transações o qual ele criou;

// Cookies <-> Formas da gente manter contexto entre requisições

// Testes
// Unitários: Unidade da sua aplicação (Formatar data) (Muitos)
// Integração: Comunicação entre duas ou mais unidades (Alguns)
// E2E - ponta a ponta: Simulam um usuário operando na nossa aplicação (Poucos)
  //  - front-end: Quem testa é o usuário final. Abre a página de login, digite o texto diego@rocketseat.com.br com ID email, clique no botão
  //  - back-end: Usuário é o front-end. Chamadas HTTP, WebSockets

// Pirâmide de testes: E2E (não dependem de nenhuma tecnologia, não dependem de arquitetura)


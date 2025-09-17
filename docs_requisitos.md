# Requisitos do Sistema — Agenda Fácil NAF

Documento com os requisitos funcionais e não funcionais para o projeto **Agenda Fácil NAF**. Destinado a orientar desenvolvimento, testes e documentação do MVP.

---

## Requisitos Funcionais (RF)


### RF1 — Cadastro de Usuário
**Descrição:** permitir que novos usuários se cadastrem.
**Fluxo:** usuário preenche formulário (nome, e-mail, matrícula opcional, telefone, senha) → validações → conta criada.


### RF2 — Autenticação (Login/Logout)
**Descrição:** permitir login com e-mail/matrícula + senha e logout.
**Fluxo:** usuário fornece credenciais → backend valida → sessão (JWT) gerada.


### RF3 — Recuperação de Senha
**Descrição:** recuperar senha por e-mail.
**Fluxo:** usuário solicita recuperação → sistema envia token/link com expiração → usuário redefine senha.


### RF4 — Listagem de Tipos de Serviço
**Descrição:** apresentar lista de serviços disponíveis no formulário de agendamento.


### RF5 — Agendamento de Atendimento
**Descrição:** permitir selecionar serviço, data e horário e confirmar agendamento.
**Fluxo:** usuário escolhe serviço → escolhe data → sistema retorna horários livres considerando duração → usuário confirma.



## Requisitos Não-Funcionais (RNF)


### RNF1 — Segurança
**Descrição:** o sistema deve garantir a segurança dos dados dos
usuários, incluindo a criptografia das senhas.



### RNF2 - Desempenho
**Descrição:** o sistema deve ser capaz de processar requisições de login e cadastro
de forma rápida e eficiente.



### RNF3 - Usabilidade
**Descrição:** a interface do sistema deve ser intuitiva e fácil de usar para todos os
tipos de usuários.


### RNF4 — Compatibilidade
**Descrição:** suporte a navegadores modernos (Chrome, Edge, Firefox, Safari) e responsividade mobile.

### RNF5 — Privacidade
**Descrição:** dados pessoais tratados conforme boas práticas; 






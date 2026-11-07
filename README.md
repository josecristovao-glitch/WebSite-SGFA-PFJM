# WebSite-SGFA-PFJM
### Website e Sistema de Gestão do Centro de Formação Académica PFJM

## 1. Sobre o projecto

Desenvolvimento de uma plataforma digital composta por duas áreas independentes e integradas:

- **Website público:** apresenta o centro, os cursos, as turmas disponíveis e permite efectuar reservas.
- **Sistema de gestão:** permite à administração e à secretaria gerir alunos, cursos, turmas, matrículas e pagamentos.

O projecto pretende melhorar a presença digital do centro e simplificar as actividades administrativas.

## 2. Funcionalidades

### 2.1. Website público
- Página inicial.
- Apresentação do centro.
- Consulta dos cursos disponíveis.
- Consulta das turmas abertas.
- Consulta de horários e preços.
- Formulário de reserva.
- Contactos e localização.

### 2.2. Sistema de gestão
- Autenticação de utilizadores.
- Gestão de administradores e funcionários da secretaria.
- Registo e consulta de alunos.
- Gestão de cursos.
- Gestão de turmas.
- Gestão de matrículas.
- Registo de pagamentos.
- Consulta de valores em dívida.
- Listagem de alunos por turma.
- Exportação básica de documentos.

## 3. Tecnologias

| Tecnologia | Utilização |
|---|---|
| HTML5 | Estrutura das páginas |
| CSS3 | Estilização e responsividade |
| JavaScript | Funcionalidades e lógica |
| Supabase | Base de dados e autenticação |
| InfinityFree | Alojamento do website |
| Git | Controlo de versões |
| GitHub | Repositório do projecto |
| Visual Studio Code | Ambiente de desenvolvimento |

## 4. Organização do projecto

```text
Centro Formacao PFJM/
│
├── website/
├── sistema/
├── database/
│   └── schema.sql
│
└── README.md
```

## 5. Perfis de acesso

**Administrador**
- Acesso geral ao sistema.
- Gestão de utilizadores.
- Gestão de cursos e turmas.
- Consulta e gestão de alunos e pagamentos.

**Secretaria**
- Registo e consulta de alunos.
- Gestão de matrículas.
- Registo de pagamentos.
- Consulta de turmas e valores em dívida.

## 6. Base de dados e segurança

A base de dados será implementada no Supabase, utilizando PostgreSQL.

A autenticação será realizada através do Supabase Auth.

As políticas de segurança (Row Level Security — RLS) deverão controlar o acesso aos dados conforme o perfil do utilizador.

A chave `service_role` nunca deverá ser exposta no código do navegador.

## 7. Alojamento

- Website público: InfinityFree.
- Base de dados e autenticação: Supabase.
- Código-fonte: GitHub.

## 8. Limites da versão

Esta versão concentra-se nas funcionalidades essenciais para colocar o centro online e permitir a gestão administrativa básica.

Funcionalidades avançadas, como gestão académica, avaliações, assiduidade, notificações automáticas e relatórios financeiros avançados, não fazem parte desta versão.

## 9. Objectivo de desenvolvimento

- Prazo previsto: 12 dias.
- Margem de segurança: 3 dias.
- Orçamento máximo: 60.000 Kz.

O prazo é uma estimativa de desenvolvimento, sujeita a testes, disponibilidade dos materiais e validação do cliente.

## 10. Estado do projecto

**Estado actual:** preparação do ambiente de desenvolvimento.

As funcionalidades serão implementadas e testadas progressivamente antes da publicação.
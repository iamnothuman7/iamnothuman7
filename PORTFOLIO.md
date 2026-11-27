# Portfólio — Emannuel Márdyan

**Desenvolvimento full stack · Engenharia de Software · Cibersegurança**

Este mapa organiza os projetos pela finalidade e pelo que está documentado nos repositórios. Ter código público não significa que uma demonstração esteja no ar ou que o sistema tenha sido auditado.

## Engenharia de software e cibersegurança — projetos locais

Aplicações e ferramentas desenvolvidas como parte dos meus estudos de **Engenharia de Software**, com execução local e testes documentados.

| Projeto | O que demonstra | Validação e escopo |
|---|---|---|
| [SecureDesk](https://github.com/iamnothuman7/securedesk) | Django, login, CRUD de tarefas e incidentes e isolamento de registros por usuário. | [28 testes](https://github.com/iamnothuman7/securedesk/blob/main/docs/VALIDATION.md) de comportamento e controles de acesso; modelo de ameaças documentado. Demonstração local. |
| [StockFlow](https://github.com/iamnothuman7/stockflow) | FastAPI e SQLite, painel de estoque, movimentações transacionais e reenvios idempotentes. | [26 testes](https://github.com/iamnothuman7/stockflow/blob/main/docs/VALIDATION.md), incluindo rollback e concorrência. Uso local e individual, sem autenticação. |
| [HTTP Security Lab](https://github.com/iamnothuman7/http-security-lab) | CLI Python offline para headers e cookies de respostas salvas, com contexto explícito e relatórios JSON/Markdown. | [38 testes](https://github.com/iamnothuman7/http-security-lab/blob/main/docs/VALIDATION.md) de contexto, entrada, relatórios e ausência de chamadas de rede nos caminhos exercitados. Sem nota ou certificação de segurança. |

## Aplicações e estudos de backend

| Projeto | O que demonstra | Contexto |
|---|---|---|
| [RADIAX](https://github.com/iamnothuman7/solvian) | Django, integração com NASA POWER, cálculos, tratamento de dados e PDF. | Projeto acadêmico. O repositório e o pacote Django mantêm o nome `solvian`; consultar as limitações de execução no README. |
| [Office AI](https://github.com/iamnothuman7/meu-escritorio-ia) | Escritório de agentes, tarefas, entregas e rotinas com Django; interface HTMX e cena 3D em módulo separado. | Ferramenta própria. A disponibilidade de cada integração está descrita no projeto. |

## Sistemas de gestão para clientes

| Projeto | Finalidade | Tecnologias documentadas |
|---|---|---|
| [Sistema Trilhas](https://github.com/iamnothuman7/sistema-trilhas) | Gestão de eventos off-road: inscrições, pagamentos, credenciamento por QR Code e financeiro. | Python, Django, Django REST Framework e Mercado Pago. |
| [Team Farias](https://github.com/iamnothuman7/team-farias) | Site e gestão de escola de vôlei: matrículas, alunos, turmas, presenças e mensalidades. | Django, PostgreSQL, HTMX e PWA. |

A apresentação desses trabalhos descreve software desenvolvido para necessidades específicas. Não implica vínculo empregatício, parceria permanente ou autorização para reutilizar marcas e dados dos clientes.

## Sites e interfaces

| Projeto | Finalidade | Contexto |
|---|---|---|
| [Emannuel Educa](https://github.com/iamnothuman7/emannuel-educa) | Lições, playground, quizzes e progresso de aprendizagem. | Protótipo frontend com dados locais ao navegador e respostas predefinidas no assistente. |
| [Emannuel Marketing](https://github.com/iamnothuman7/emannuel.mkt) | Apresentação profissional e serviços criativos. | Site em HTML, CSS e JavaScript. |
| [Trilhão Paracuru](https://github.com/iamnothuman7/trilhaoparacuru) | Divulgação do 7º Trilhão Paracuru Off-Road, edição 2026. | Site estático de uma edição do evento, com inscrições direcionadas a uma plataforma externa. |
| [Ibiapaba Solar](https://github.com/iamnothuman7/ibiapaba-solar) | Simulação de economia com energia solar compartilhada. | Implementação no navegador; entrada convencional em `index.html`. |

## Protótipos e versões relacionadas

| Repositório | Papel no conjunto |
|---|---|
| [calculadora](https://github.com/iamnothuman7/calculadora) | Protótipo inicial de simulação solar e aprendizado de interfaces. |
| [ibiapaba-solar-calculator](https://github.com/iamnothuman7/ibiapaba-solar-calculator) | Implementação atualmente equivalente à do Ibiapaba Solar, com outro arquivo de entrada e histórico separado. |
| [movimenta-mais](https://github.com/iamnothuman7/movimenta-mais) | Estudo derivado do Astro Supabase Starter da Netlify. A origem e os créditos estão preservados; não é apresentado como produto próprio concluído. |

## Como explorar

Leia o README de cada projeto para entender o objetivo, a execução local, a origem do código e as limitações. Os repositórios mantêm seus próprios históricos e comandos; este mapa é um índice, não uma migração de código.

[Voltar ao perfil](./README.md)

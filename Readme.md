## Projeto de Software — Repositório da Disciplina

Este repositório será utilizado na disciplina de Projetos de Software para organizar materiais, atividades, artefatos de engenharia, documentação e código produzido ao longo do curso.

### Objetivos
- **Centralizar materiais**: artigos, slides, referências e exemplos.
- **Apoiar o desenvolvimento**: manter artefatos (visão, requisitos, modelagem, testes) e código-fonte.
- **Promover boas práticas**: versionamento, revisão por pares, testes, integração contínua e documentação.

### Estrutura do Repositório
- `Artigos/`: materiais de leitura e referências utilizadas na disciplina.
- `Readme.md`: visão geral do repositório e orientações de uso.

Sugestão de pastas que podem ser adicionadas conforme a evolução do curso/projeto:
- `docs/`: documentação do projeto (visão, requisitos, arquitetura, decisões ADR, manuais).
- `src/`: código-fonte do(s) projeto(s).
- `tests/`: testes automatizados.
- `scripts/`: utilitários e automações.
- `planning/`: cronogramas, backlog, sprints e métricas.

### Como Contribuir
1. Crie uma branch a partir da `main` usando um nome descritivo:
   - `feature/nome-da-funcionalidade`
   - `fix/descricao-breve`
   - `docs/assunto-da-documentacao`
2. Faça commits pequenos e frequentes (veja Convenções de Commit abaixo).
3. Abra um Pull Request (PR) para `main`, descrevendo claramente o que foi feito.
4. Solicite revisão de colegas. Enderece comentários antes de fazer o merge.

### Convenções de Commit (Commits Semânticos)
Use o formato: `tipo(escopo): mensagem breve`
- `feat`: nova funcionalidade
- `fix`: correção de bug
- `docs`: documentação
- `test`: testes
- `refactor`: refatoração (sem mudar comportamento externo)
- `chore`: tarefas diversas (build, configs)
- `perf`: melhoria de desempenho
- `style`: mudanças que não afetam a lógica (lint, formatação)

Exemplos:
- `feat(api): adicionar endpoint de autenticação`
- `docs(arquitetura): registrar decisão ADR sobre camadas`

### Fluxo de Trabalho com Git (GitFlow simplificado)
1. `main` sempre estável e revisada.
2. Desenvolva em branches de feature/fix.
3. Abra PR para `main` com descrição, checklist e referência a issues.
4. Após revisão e validação (tests/checks), faça o merge com squash ou rebase conforme combinado pelo time.

### Issues e PRs
- **Issues**: descreva contexto, problema, definição de pronto (DoD) e critérios de aceitação.
- **PRs**: inclua objetivo, mudanças principais, como testar, screenshots (se aplicável) e impactos.
- Referencie issues no PR usando `Closes #<número>` quando aplicável.

### Qualidade e Boas Práticas
- Escreva código legível, coeso e com testes.
- Adote revisão por pares (peer review) em todos os PRs.
- Documente decisões arquiteturais (ADR) em `docs/adr/`.
- Mantenha o `Readme.md` e o `docs/` atualizados.

### Requisitos (ajuste conforme o projeto)
- Git instalado e acesso ao GitHub.
- Ferramentas do stack do projeto (a definir). Se aplicável, documente versões mínimas, dependências e como executar o ambiente local em `docs/setup.md`.

### Cronograma (exemplo)
- Semana 1–2: alinhamento de escopo e visão do produto.
- Semana 3–4: levantamento de requisitos e prototipagem.
- Semana 5–6: arquitetura e planejamento da implementação.
- Semana 7–10: desenvolvimento incremental com sprints.
- Semana 11–12: testes, validação e documentação final.

### Licença
Licença a definir pelo professor/time. Sugestão: MIT. Adicionar arquivo `LICENSE` quando definido.

### Contato
- Dúvidas e sugestões: utilize as Issues do repositório ou canal da turma.

---
Mantenha este arquivo atualizado conforme o andamento da disciplina e do projeto.
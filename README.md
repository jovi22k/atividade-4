# Entregáveis - Atividade 4 (CI/CD - React, Node, PostgreSQL)

Esses arquivos atendem aos requisitos descritos no enunciado da atividade. Consulte também o enunciado original para evidências e prints requisitados. (Referência: veja o enunciado da disciplina). 

## Conteúdo deste pacote
- `.github/workflows/ci-cd.yml` — workflow de CI (frontend + backend + migrations test) e CD (staging + produção com aprovação).
- `backend/Dockerfile` — Dockerfile para aplicação Node.
- `frontend/Dockerfile` — Dockerfile para aplicação React (build + Nginx).
- `docker-compose.yml` — ambiente de desenvolvimento com Postgres, backend e frontend.
- `backend/package.json`, `frontend/package.json` — scripts de build/test/migrate exemplares.
- `backend/migrations/` — migrations de exemplo (001_create_users.sql).
- `README.md` (este arquivo) — instruções para rodar localmente e checklist de evidências.
- `REPORT_TEMPLATE.md` — modelo de relatório com as screenshots listadas na atividade.
- `JIRA_TEMPLATE.md` — exemplo de Épico / Story / Task.
- `PR_TEMPLATE.md` — template para Pull Requests.
- `COMMIT_CONVENTION.md` — convenção de commits.
- `.env.example` — exemplos de variáveis de ambiente.

## Como usar (local)
1. Ajuste as variáveis em `backend/.env.example` e `frontend/.env.example`.
2. Rode `docker-compose up --build` (requer Docker).
3. Backend disponível em `http://localhost:3000`; frontend em `http://localhost:3001`.

## Evidências solicitadas (resumo)
- Prints do Jira (Quadro com Épico, Sprint ativa, Tarefa com integração GitHub).  
- Prints do GitHub (commits, PR merged, network graph).  
- Prints do GitHub Actions (arquivo workflow e execuções).  
- Links públicos: repositório GitHub e projeto Jira (convidar claudinei.dias@catolicasc.org.br).

Salve este diretório no seu repositório e faça commits/PRs seguindo os templates. Boa sorte!

# 📚 Biblioteca de Comandos Git/GitHub

> Coleção organizada de comandos para consulta rápida e eficiente

## 🔍 Busca Rápida

| Comando | Categoria | Descrição | Link |
|---------|-----------|-----------|------|
| `git init` | Repositórios | Inicializar novo repositório | [Ver](#01-repositórios) |
| `git clone` | Repositórios | Clonar repositório existente | [Ver](#01-repositórios) |
| `git add` | Staging | Adicionar arquivos ao staging | [Ver](#04-staging) |
| `git commit` | Commits | Criar commit | [Ver](#03-commits) |
| `git push` | Remotos | Enviar para repositório remoto | [Ver](#05-remotos) |
| `git pull` | Remotos | Trazer alterações do remoto | [Ver](#05-remotos) |
| `git branch` | Branches | Gerenciar branches | [Ver](#02-branches) |
| `git checkout` | Branches | Mudar entre branches | [Ver](#02-branches) |
| `git merge` | Branches | Unir branches | [Ver](#02-branches) |
| `git status` | Staging | Verificar estado do repositório | [Ver](#04-staging) |
| `git log` | Commits | Ver histórico de commits | [Ver](#03-commits) |

## 📂 Índice por Categorias

### 01. 📁 [Repositórios](01-repositorios/)
- [git init](01-repositorios/criar.md) - Inicializar repositório local
- [git clone](01-repositorios/clonar.md) - Clonar repositório remoto
- [git remote](01-repositorios/remoto.md) - Gerenciar repositórios remotos

### 02. 🌿 [Branches](02-branchs/)
- [git branch](02-branchs/gerenciar.md) - Listar/criar/excluir branches
- [git checkout](02-branchs/mudar.md) - Mudar entre branches
- [git switch](02-branchs/mudar.md) - Nova forma de mudar branches (Git 2.23+)
- [git merge](02-branchs/merge.md) - Unir branches
- [git rebase](02-branchs/rebase.md) - Reaplicar commits

### 03. 💾 [Commits](03-commits/)
- [git commit](03-commits/criar.md) - Criar commit
- [git log](03-commits/historico.md) - Ver histórico
- [git show](03-commits/detalhes.md) - Ver detalhes do commit
- [git amend](03-commits/corrigir.md) - Corrigir último commit

### 04. 📦 [Staging](04-staging/)
- [git add](04-staging/adicionar.md) - Adicionar ao staging
- [git status](04-staging/status.md) - Verificar estado
- [git reset](04-staging/reset.md) - Remover do staging
- [git diff](04-staging/diff.md) - Ver diferenças

### 05. ☁️ [Remotos](05-remotos/)
- [git push](05-remotos/enviar.md) - Enviar para remoto
- [git pull](05-remotos/trazer.md) - Trazer do remoto
- [git fetch](05-remotos/fetch.md) - Buscar do remoto
- [git remote](05-remotos/gerenciar.md) - Gerenciar conexões remotas

### 06. 🔄 [Pull Requests](06-pull-requests/)
- [Criar PR](06-pull-requests/criar.md) - Criar Pull Request
- [Revisar PR](06-pull-requests/revisar.md) - Comandos para revisão
- [Merge PR](06-pull-requests/merge.md) - Mesclar Pull Request

### 07. 🐛 [Issues](07-issues/)
- [Vincular commits](07-issues/vincular.md) - Commits com referência a issues
- [Fechar via commit](07-issues/fechar.md) - Fechar issue via mensagem de commit

### 08. 🚀 [Git Flow](08-git-flow/)
- [Fluxo básico](08-git-flow/basico.md) - Fluxo de trabalho padrão
- [Feature branches](08-git-flow/feature.md) - Trabalhando com features
- [Hotfix](08-git-flow/hotfix.md) - Correções de emergência

### 09. ⚡ [Avançado](09-avancado/)
- [git stash](09-avancado/stash.md) - Guardar alterações temporárias
- [git tag](09-avancado/tags.md) - Gerenciar tags/versões
- [git bisect](09-avancado/bisect.md) - Encontrar commit com bug

### 10. 🔧 [GitHub CLI](10-github-cli/)
- [gh auth](10-github-cli/auth.md) - Autenticação
- [gh pr](10-github-cli/pr.md) - Gerenciar PRs via CLI
- [gh issue](10-github-cli/issue.md) - Gerenciar issues via CLI

### 11. ⌨️ [Atalhos](11-atalhos/)
- [GitHub Web](11-atalhos/web.md) - Atalhos do site GitHub
- [GitHub Desktop](11-atalhos/desktop.md) - Atalhos do app desktop

### 12. ⚙️ [Workflows](12-workflows/)
- [GitHub Actions](12-workflows/actions.md) - Automações básicas
- [Exemplos](12-workflows/exemplos.md) - Workflows prontos

## 🛠️ [Ferramentas](ferramentas/)
- [Índice de busca](ferramentas/search-index.json) - Para scripts de busca
- [Cheatsheet PDF](ferramentas/cheatsheet.pdf) - Resumo para impressão

## 🚀 Como Usar

1. **Busca rápida**: Use Ctrl+F (Cmd+F no Mac) nesta página
2. **Navegação**: Clique na categoria desejada
3. **Busca avançada**: Consulte o arquivo JSON em `ferramentas/search-index.json`

## 🔄 Mantenha Atualizado

```bash
# Para atualizar seu repositório local
git pull origin main

# Para sugerir novos comandos
# Abra uma issue no repositório ou faça um PR

git remote add origin https://github.com/seu-usuario/seu-repositorio.git

# Changelog

## [1.0.1] - 2026-06-13

### Adicionado
- GitHub Actions: workflow `validate.yml` para validar o pacote em PRs e pushes no `main`
- GitHub Actions: workflow `release.yml` para publicar automaticamente no VS Code Marketplace ao criar uma tag `v*`
- Seção CI/CD no README com instruções de release
- `@vscode/vsce` como `devDependency` no `package.json`

### Alterado
- `.vscodeignore` agora exclui `.github/` do pacote distribuído
- README: imagens de preview descomentadas (adicionar `images/dark-preview.png` e `images/light-preview.png`)

## [1.0.0] - 2026-06-13

### Adicionado
- Ícone oficial da extensão com as cores do Coritiba Football Club
- Campos `homepage` e `bugs` no `package.json` para melhor integração com o Marketplace
- README completo com badges, lista de linguagens suportadas, paleta de cores e guia de contribuição

### Alterado
- Versão promovida para 1.0.0 — lançamento estável para o VS Code Marketplace
- Palavras-chave `futebol` e `coxa` adicionadas para melhor descoberta no Marketplace

## [0.0.2] - 2026-03-15

### Adicionado
- Suporte a sintaxe Dart, Swift, Vue, Angular e Svelte no tema claro
- Regras de realce para variáveis SQL, Dockerfile e alias GraphQL no tema claro

### Corrigido
- Tema claro estava incompleto em relação ao tema escuro

## [0.0.1] - 2025-11-01

### Adicionado
- Versão inicial do tema
- Tema escuro (Dark)
- Tema claro (Light)

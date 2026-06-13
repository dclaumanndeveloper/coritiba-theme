# Coritiba Theme

[![Versão](https://img.shields.io/visual-studio-marketplace/v/DiegoRamosClaumann.coritiba-theme?style=flat-square&label=Vers%C3%A3o&color=00593f)](https://marketplace.visualstudio.com/items?itemName=DiegoRamosClaumann.coritiba-theme)
[![Downloads](https://img.shields.io/visual-studio-marketplace/d/DiegoRamosClaumann.coritiba-theme?style=flat-square&label=Downloads&color=00593f)](https://marketplace.visualstudio.com/items?itemName=DiegoRamosClaumann.coritiba-theme)
[![Avaliações](https://img.shields.io/visual-studio-marketplace/r/DiegoRamosClaumann.coritiba-theme?style=flat-square&label=Avalia%C3%A7%C3%A3o&color=00593f)](https://marketplace.visualstudio.com/items?itemName=DiegoRamosClaumann.coritiba-theme)
[![Licença](https://img.shields.io/github/license/dclaumanndeveloper/coritiba-theme?style=flat-square&label=Licen%C3%A7a&color=00593f)](LICENSE)
[![VS Code](https://img.shields.io/badge/VS%20Code-1.80%2B-007ACC?style=flat-square)](https://code.visualstudio.com)

Tema de cores para o Visual Studio Code inspirado nas cores oficiais do **Coritiba Football Club** — o maior clube do Paraná. Verde e branco na sua tela de desenvolvimento.

**Vamos Coxa! 🟢⚪**

---

## Pré-visualização

### Tema Escuro

![Coritiba Theme Dark](images/dark-preview.png)

### Tema Claro

![Coritiba Light](images/light-preview.png)

---

## Características

- **Tema Dark** — fundo verde escuro (`#0d2818`) com interface nas cores do Coritiba
- **Tema Light** — fundo branco com elementos verdes do clube
- **Interface completa** — barra de status, abas, painel, terminal, sidebar e activity bar todos tematizados
- **Sintaxe para 20+ linguagens** — cobertura detalhada por linguagem (veja lista abaixo)
- **Destaque especial** — tipo `any` do TypeScript aparece em vermelho com sublinhado para alertar sobre tipagem fraca
- **Git decorations** — arquivos modificados, adicionados e ignorados com cores distintas
- **Debug & Testing** — ícones de debug e testing integrados ao tema

---

## Instalação

### Via VS Code Marketplace (recomendado)

1. Abra o VS Code
2. Vá em **Extensions** (`Ctrl+Shift+X` / `Cmd+Shift+X`)
3. Busque por `Coritiba Theme`
4. Clique em **Install**

### Via linha de comando

```bash
code --install-extension DiegoRamosClaumann.coritiba-theme
```

### Via arquivo `.vsix`

1. Baixe o arquivo `.vsix` na [página de releases](https://github.com/dclaumanndeveloper/coritiba-theme/releases)
2. No VS Code: `Ctrl+Shift+P` → `Extensions: Install from VSIX...`
3. Selecione o arquivo baixado

### Para desenvolvimento

1. Clone o repositório:
   ```bash
   git clone https://github.com/dclaumanndeveloper/coritiba-theme.git
   ```
2. Copie a pasta para o diretório de extensões do VS Code:
   - **Windows:** `%USERPROFILE%\.vscode\extensions\`
   - **macOS / Linux:** `~/.vscode/extensions/`
3. Reinicie o VS Code

---

## Ativação do tema

1. `Ctrl+Shift+P` (ou `Cmd+Shift+P` no macOS) → `Preferences: Color Theme`
2. Selecione **Coritiba Theme** (escuro) ou **Coritiba Light** (claro)

---

## Paleta de cores

### Cores da interface

| Nome              | Hex       | Uso                                      |
|-------------------|-----------|------------------------------------------|
| Verde oficial     | `#00593f` | Sidebar, status bar, botões primários    |
| Verde escuro      | `#003d2b` | Title bar, tab bar, headers              |
| Verde profundo    | `#0d2818` | Fundo do editor (tema escuro)            |
| Verde médio       | `#00452f` | Bordas e separadores                     |
| Verde claro       | `#4caf50` | Cursor, badges, gutter de adições        |
| Verde suave       | `#a5d6a7` | Texto secundário, itens inativos         |
| Branco            | `#ffffff` | Texto ativo, foreground                  |

### Cores de sintaxe (tema escuro)

| Elemento                  | Cor                          |
|---------------------------|------------------------------|
| Comentários               | `#6A9955` _itálico_          |
| Palavras-chave            | `#569CD6`                    |
| Controle de fluxo         | `#C586C0`                    |
| Strings                   | `#CE9178`                    |
| Números                   | `#B5CEA8`                    |
| Booleans / null           | `#569CD6`                    |
| Variáveis                 | `#9CDCFE`                    |
| Funções                   | `#DCDCAA`                    |
| Classes / tipos           | `#4EC9B0`                    |
| Propriedades              | `#9CDCFE`                    |
| Tipo `any` (TypeScript)   | `#FF1744` **negrito sublinhado** |
| Regex                     | `#D16969`                    |

---

## Linguagens suportadas

Regras de sintaxe detalhadas por linguagem:

| Linguagem              | Cobertura                                               |
|------------------------|---------------------------------------------------------|
| JavaScript / JSX       | Variáveis, funções, classes, template literals, regex   |
| TypeScript / TSX       | Tipos, interfaces, generics, decorators, `any` destacado|
| Python                 | Imports, tipos, builtins, docstrings, parâmetros        |
| Java                   | Tipos primitivos, classes, anotações, funções           |
| Kotlin                 | Definições, classes                                     |
| C / C++                | Tipos, typedef, struct, preprocessor                    |
| C#                     | Tipos, classes, propriedades, atributos                 |
| Go                     | Tipos, funções, variáveis de atribuição                 |
| Rust                   | Tipos, funções, lifetimes, atributos, `use`             |
| PHP                    | Variáveis `$`, funções, classes, `$this`                |
| Ruby                   | Variáveis de instância/classe, símbolos, interpolação   |
| Shell / Bash           | Builtins, variáveis, heredocs                           |
| Markdown               | Headings, bold, italic, links, code blocks, blockquotes |
| JSON                   | Chaves, valores string, valores em arrays               |
| YAML                   | Tags, valores, timestamps, documentos                   |
| TOML                   | Chaves, seções                                          |
| SQL                    | DML/DDL keywords, tabelas, funções, colunas             |
| GraphQL                | Tipos, fragmentos, variáveis, operações, aliases        |
| Dockerfile             | Instruções, imagens, variáveis                          |
| Dart                   | Tipos primitivos, classes, funções                      |
| Swift                  | Tipos, classes, funções                                 |
| Vue / Angular / Svelte | Tags, atributos, componentes, seletores                 |
| INI / Properties       | Definições, seções                                      |

---

## Destaque especial: tipo `any` no TypeScript

O tipo `any` no TypeScript aparece em **vermelho vivo com sublinhado** (`#FF1744`, negrito+sublinhado) nos dois temas. Isso serve como alerta visual para uso inadequado de tipagem dinâmica, encorajando o uso de tipos explícitos.

```typescript
// ⚠️ Este tipo aparece destacado em vermelho:
function processData(value: any) { ... }

// ✅ Prefira tipos explícitos:
function processData(value: string | number) { ... }
```

---

## CI/CD

| Workflow | Trigger | Ação |
|---|---|---|
| `validate.yml` | Push/PR em `main` | Valida o pacote `.vsix` |
| `release.yml` | Tag `v*` (ex: `v1.1.0`) | Publica no Marketplace + cria release no GitHub |

Para publicar uma nova versão:
1. Atualize a versão em `package.json` e em `CHANGELOG.md`
2. Commit e crie uma tag: `git tag v1.1.0 && git push origin v1.1.0`
3. O workflow cuida do resto (requer secret `VSCE_PAT` configurado no repositório)

---

## Contribuindo

Contribuições são muito bem-vindas!

1. Faça um fork do repositório
2. Crie uma branch para sua feature: `git checkout -b feature/minha-melhoria`
3. Faça suas alterações nos arquivos em `themes/`
4. Teste localmente copiando a pasta para `~/.vscode/extensions/`
5. Abra um Pull Request com descrição das mudanças

### Reportando problemas

Abra uma [issue no GitHub](https://github.com/dclaumanndeveloper/coritiba-theme/issues) descrevendo:
- Linguagem ou elemento com problema de cor
- Versão do VS Code
- Tema utilizado (escuro ou claro)
- Screenshot se possível

---

## Licença

Distribuído sob a licença [MIT](LICENSE).

---

**Feito com 💚 para a Nação Alviverde**

**Vamos Coxa! 🟢⚪**

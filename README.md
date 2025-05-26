
# 💻 Configurações Pessoais do VS Code

Este repositório contém meu arquivo de configurações do Visual Studio Code (`settings.json`), cuidadosamente ajustado para produtividade, foco, performance e legibilidade — especialmente em projetos com JavaScript/TypeScript, React e Node.js.

---

## ✨ Principais Características

### 🛠️ Ações Automáticas ao Salvar
- ✅ Correção automática com ESLint, TypeScript, etc.
- 📦 Organização de imports automaticamente.

```json
"editor.codeActionsOnSave": {
  "source.fixAll": "always",
  "source.organizeImports": "always"
}
```

---

### 🎨 Formatação com Prettier
- Prettier como formatador padrão para JS, TS, JSX e TSX.
- Formatação automática ao salvar.
- Arquivo `.prettierrc` usado como referência.

---

### 🧠 Editor Focado e Leve
- Minimap, scrollbars e breadcrumbs desativados.
- Sugestões inline desativadas (ex: Copilot).
- Cursor sólido, sem piscar.
- Layout limpo e sem distrações.

---

### ✍️ Fonte e Tipografia
- Fontes com ligaduras: `JetBrains Mono`, `Fira Code` e outros fallbacks.
- Fonte tamanho 14, com espaçamento de linha aumentado para melhor leitura.

---

### 📁 Organização de Arquivos
- Estrutura de pastas completa no Explorer.
- Agrupamento automático de arquivos relacionados (`.env`, `tailwind.config`, etc.).
- Ordem de exibição: pastas → arquivos.

---

### 🧹 Interface Minimalista
- Sem tela inicial, menu superior, nem barra de status.
- Ícones de arquivos via tema `a-file-icon-vscode`.

---

### 🖥️ Terminal Integrado
- Shell padrão configurado (`fish`, login shell no Linux/macOS).
- Aceleração por GPU ativada.
- Sem alertas ao sair, nem reinicialização automática por extensões.

---

### 🔍 Sugestões e Imports
- Auto-imports habilitados para JS/TS.
- Atualização automática de imports ao mover arquivos.
- Preferência por `import type` quando aplicável.

---

### ✅ Integração com ESLint e GitLens
- ESLint ativo para arquivos `.js`, `.ts`, `.jsx`, `.tsx`, `.graphql`.
- GitLens mostra autor e última alteração no código diretamente.

---

### 🔐 Segurança e Extensões
- Arquivos não confiáveis abrem em nova janela.
- Atualização manual de extensões (melhor controle).
- Live Server e clientes de banco de dados ajustados para não interromper o fluxo.

---

### 💾 Auto Salvamento
- Salva automaticamente ao sair de uma aba ou trocar de janela.

---

### 🧭 Navegação e Abas
- Abas sempre abertas (sem preview).
- Abas lado a lado abrem à direita.
- Botão de fechar à direita + ícones visíveis.

---

### ⚡ Performance
- Symlinks ignorados nas buscas.
- Atualizações automáticas de extensões desativadas.
- Atualizações do VS Code feitas manualmente.

---

## 📂 Como Usar

1. Copie o conteúdo do `settings.json` para sua pasta `.vscode/` ou abra o atalho `Ctrl+Shift+P → Preferences: Open Settings (JSON)` e cole diretamente.
2. Instale extensões recomendadas (Ex: `Prettier`, `ESLint`, `GitLens`, `a-file-icon-vscode`).
3. Configure seu terminal (`fish`, `zsh`, etc.) se quiser aproveitar ao máximo.

---

## ✅ Requisitos Recomendados

- Fonte: [JetBrains Mono Nerd Font](https://www.nerdfonts.com/font-downloads)
- Extensões:
  - `esbenp.prettier-vscode`
  - `dbaeumer.vscode-eslint`
  - `eamodio.gitlens`
  - `a-file-icon-vscode`
  - `ritwickdey.liveserver` (opcional)

---

## 📜 Licença

Este repositório está licenciado sob a [MIT License](LICENSE).

---

🔧 Sinta-se à vontade para clonar, adaptar e contribuir com melhorias!

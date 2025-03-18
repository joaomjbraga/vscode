# 💻 Minhas Configurações do VS Code

Este repositório contém minhas configurações personalizadas do Visual Studio Code. Se você gosta de um ambiente minimalista e focado em produtividade, pode testar e adaptar ao seu gosto! 🚀

## 🎨 Temas e Aparência
- **Tema**: [Rosé Pine Moon](https://marketplace.visualstudio.com/items?itemName=rose-pine.rose-pine)
- **Ícones**: [symbols](https://marketplace.visualstudio.com/items?itemName=ryuta46.symbols)
- **Fonte do Editor**: JetBrains Mono
- **Fonte do Terminal**: FiraCode Nerd Font
- **Configurações Visuais**:
  - Barra de status oculta
  - Minimap desativado
  - Breadcrumbs desativados
  - Barra de menus oculta

## ⚙️ Configuração do `settings.json`
```json
{
  "editor.fontFamily": "JetBrains Mono, Menlo, Monaco, Courier New, monospace",
  "editor.fontWeight": "normal",
  "editor.fontSize": 13,
  "editor.lineHeight": 1.5,
  "editor.letterSpacing": 0,
  "editor.fontLigatures": true,
  "editor.renderLineHighlight": "gutter",
  "editor.wordWrap": "on",
  "editor.minimap.enabled": false,
  "editor.scrollbar.horizontal": "hidden",
  "editor.scrollbar.vertical": "hidden",
  "editor.semanticHighlighting.enabled": false,
  "editor.cursorBlinking": "solid",
  "editor.lineNumbers": "relative",
  "editor.stickyScroll.enabled": false,
  "workbench.colorTheme": "Rosé Pine Moon",
  "workbench.iconTheme": "symbols",
  "workbench.startupEditor": "none",
  "workbench.activityBar.location": "default",
  "workbench.editor.labelFormat": "short",
  "workbench.layoutControl.enabled": false,
  "workbench.tree.indent": 16,
  "workbench.statusBar.visible": false,
  "explorer.compactFolders": false,
  "breadcrumbs.enabled": false,
  "window.commandCenter": false,
  "window.titleBarStyle": "native",
  "window.menuBarVisibility": "hidden",
  "terminal.integrated.fontFamily": "FiraCode Nerd Font",
  "terminal.integrated.fontSize": 13,
  "terminal.integrated.fontLigatures.enabled": true,
  "terminal.integrated.tabs.enabled": false,
  "git.autofetch": true
}
```

## 🔌 Extensões Recomendadas
Aqui estão algumas extensões que podem ajudar a melhorar a produtividade:

### 📌 Produtividade e Qualidade de Código
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

### 🌐 Desenvolvimento Web
- [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
- [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)
- [JavaScript (ES6) Code Snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
- [Tabnine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode)

### 📦 Frameworks e Bibliotecas
- [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
- [Vue Language Features (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.volar)
- [React Developer Tools](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
- [Thunder Client](https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client)

## 🚀 Como Usar Minhas Configurações
1. **Copie o conteúdo do `settings.json`** e cole no seu próprio VS Code (`Ctrl + Shift + P` → "Preferences: Open Settings (JSON)").
2. **Instale as extensões recomendadas** manualmente ou use o comando:
   ```sh
   code --install-extension nome.da.extensao
   ```
3. **Reinicie o VS Code** para aplicar todas as configurações.

---
Gostou das configurações? Fique à vontade para contribuir e sugerir melhorias! 😊


# 🖥️ Configurações Minimalistas do meu VSCode  

Um setup focado em **simplicidade**, **produtividade** e **design clean** para programar com o Visual Studio Code!  
---

## ✨ Destaques do Setup  
- **Fonte:** `JetBrains Mono` (ideal para programadores, com suporte a ligaturas).  
- **Tema:** `Min Dark` (minimalista e agradável aos olhos).  
- **Terminal padrão:** `Git Bash` (experiência Unix-like no Windows).  
- **Minimalismo:** Barra de atividades, minimapa e breadcrumbs desativados.  
- **Foco na legibilidade:** Altura da linha ajustada e quebra automática de linha habilitada.  

---

## 🔧 Configurações Detalhadas  

### 🖋️ **Estilo de Texto**
- **Fonte:** JetBrains Mono  
- **Tamanho da fonte:** 14px  
- **Altura da linha:** 1.8  
- **Ligaduras:** Ativadas para suavizar operadores como `=>`, `===`, etc.  

### 📜 **Editor**
- **Quebra automática de linha:** Sempre habilitada (`wordWrap: "on"`).  
- **Destaque da linha atual:** Apenas no *gutter* (menos poluição visual).  
- **Regras verticais:** 80 e 120 colunas para manter o código organizado.  
- **Minimapa:** Desabilitado para foco total no código.  
- **Barras de rolagem:** Ocultas para um layout mais limpo.  

### 🎨 **Aparência**
- **Tema de cores:** Min Dark 🌙  
- **Tema de ícones:** Symbols 🛠️  
- **Barra de atividades:** Oculta para reduzir distrações.  
- **Breadcrumbs:** Desativados para um visual mais enxuto.  

### 💻 **Terminal Integrado**
- **Fonte:** JetBrains Mono  
- **Tamanho da fonte:** 14px  
- **Ligaturas no terminal:** Ativadas.  
- **Terminal padrão no Windows:** Git Bash 🐧  

---
## 📂 Configurações Completas  


    ```json

    {
        "editor.fontFamily": "JetBrains Mono",
        "editor.fontSize": 14,
        "editor.lineHeight": 1.8,
        "editor.renderLineHighlight": "gutter",
        "editor.rulers": [80, 120],
        "editor.fontLigatures": true,
        "editor.wordWrap": "on",
        "editor.minimap.enabled": false,
        "editor.scrollbar.horizontal": "hidden",
        "editor.scrollbar.vertical": "hidden",
        "editor.semanticHighlighting.enabled": false,
        "workbench.startupEditor": "newUntitledFile",
        "workbench.colorTheme": "Min Dark",
        "workbench.iconTheme": "symbols",
        "workbench.activityBar.location": "hidden",
        "workbench.editor.labelFormat": "short",
        "workbench.layoutControl.enabled": false,
        "explorer.compactFolders": false,
        "breadcrumbs.enabled": false,
        "window.commandCenter": false,
        "window.menuBarVisibility": "compact",
        "window.titleBarStyle": "custom",
        "terminal.integrated.fontFamily": "JetBrains Mono",
        "terminal.integrated.fontSize": 14,
        "terminal.integrated.fontLigatures": true,
        "terminal.integrated.defaultProfile.windows": "Git Bash"
    }

# 🎯 Benefícios
- Produtividade máxima: Nada de distrações, apenas código.
- Visual agradável: Um tema escuro confortável para longas sessões de codificação.
- Organização: Regras de 80 e 120 colunas ajudam no estilo de código limpo.


💡 Dica: Experimente combinar estas configurações com extensões como Prettier, ESLint ou GitLens para turbinar ainda mais o seu VSCode!
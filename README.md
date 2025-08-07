# VS Code Settings

Este repositório contém minhas configurações personalizadas do **Visual Studio Code**, otimizadas para um ambiente de desenvolvimento mais fluido, limpo e organizado.

## Configurações incluídas

- 🎨 **Tema de ícones:** `material-icon-theme`
- 💾 **Salvamento automático:** Após um pequeno atraso (`afterDelay`)
- 📏 **Altura da linha no editor:** `1.8`
- ✍️ **Destaque da linha ativa:** Apenas na *gutter* (margem)
- 🔤 **Fonte:** JetBrains Mono, tamanho `17`, sem ligaduras
- 📁 **Exploração de pastas:** Folders não compactados
- 🔄 **Sincronização automática do cliente de banco de dados:** Ativada
- 🛡️ **Arquivos não confiáveis:** Abertos automaticamente (sem prompt)
- 🗑️ **Confirmação ao deletar arquivos:** Desativada
- 📊 **Telemetria da Red Hat:** Ativada
- 🗺️ **Minimapa do editor (miniatura de código):** Desativada

## Como usar estas configurações

1. Abra o Visual Studio Code.
2. Pressione `Ctrl + ,` (ou vá em **File > Preferences > Settings**).
3. Clique no ícone de engrenagem no canto superior direito da tela e selecione **"Open Settings (JSON)"**.
4. Copie o conteúdo do arquivo [`settings.json`](settings.json) deste repositório.
5. Cole no seu arquivo de configurações.

---

## Comando adicional (exemplo útil)

```json
"terminal.integrated.cwd": "C:\\Users\\Juan\\Documents"
```

Esse comando inicializa o terminal do VS Code no diretório `Documents`. Altere o caminho conforme o usuário ou sistema.

---

## Contribuições

Sugestões são sempre bem-vindas! Sinta-se à vontade para abrir um **Pull Request** com melhorias ou suas próprias configurações. 😄
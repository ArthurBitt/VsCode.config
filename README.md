# VsCode.config

```powershell

Get-ExecutionPolicy
Set-ExecutionPolicy unrestricted -Force

```

```json


{
    "workbench.iconTheme": "a-file-icon-vscode",
    "workbench.colorTheme": "OM Theme (Night Owl Italic)",
    "window.zoomLevel": 3,
    "workbench.productIconTheme": "a-file-icon-vscode-product-icon-theme",
    "files.autoSave": "afterDelay",
    "workbench.startupEditor": "none", // sem pagina inicial
    "editor.fontFamily": "Consolas, 'Courier New', monospace",
    "explorer.compactFolders": false, // subdiretorios
    "code-runner.runInTerminal": true, // tira do output
    "code-runner.clearPreviousOutput": false, // limpa a seção anterior ao código
    "code-runner.executorMap": {
        "python": "cls ; python -u" 
       
    },// limpa o terminal e roda o código
    "code-runner.ignoreSelection": true, // nao trava se tiver com parte do codigo selecionado
    "python.defaultInterpreterPath": "python" // seta um interpretador padrao
}       
```

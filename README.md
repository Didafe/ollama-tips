# COMANDOS PARA RODAR OLLAMA com interface Open WebUI

### Iniciar o Servidor:

```bash
ollama serve
```

### Iniciando um modelo ollama no CMD:

```bash
ollama run llama3.2:3b
```

### Iniciando a interface gráfica Open WebUI - Abrir a porta: http://127.0.0.1:8080:

```bash
docker run -d --network=host -v open-webui:/app/backend/data -e OLLAMA_BASE_URL=http://127.0.0.1:11434 --name open-webui --restart always ghcr.io/open-webui/open-webui:main
```
>IMPORTANTE
>
>NÃO ESQUEÇA DE INICIAR O DOCKER PARA RODAR A INTERFACE GRÁFICA OPEN WEBUI.

### Site Ollama:

>https://ollama.com


### Repositório Open WebUI:
>https://github.com/open-webui/open-webui

### Site Open WebUI:
>https://openwebui.com/
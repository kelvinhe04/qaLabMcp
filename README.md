# qaLabMcp — Servidor MCP local con GitHub Copilot

Servidor MCP en Python que expone herramientas (tools) para pruebas de calidad de software, consumidas desde GitHub Copilot Chat en modo Agent vía protocolo MCP por stdio.

## Estructura del proyecto

```
qaLabMcp/
├── capturas/              ← Evidencias (capturas de pantalla)
├── .vscode/mcp.json       ← Registro del servidor MCP
├── server.py              ← Servidor MCP (3 tools base + 4 retos)
├── datos_prueba.json      ← Datos de prueba para Reto 4
├── .gitignore
└── README.md
```

## Evidencias

Tres capturas por cada prueba/reto: tool visible en Copilot, prompt usado y resultado devuelto.

### Prueba A (3 capturas: tool, prompt, resultado)

| Tool | Prompt | Resultado |
|------|--------|-----------|
| ![tool](capturas/prueba-a/tool.png) | ![prompt](capturas/prueba-a/prompt.png) | ![resultado](capturas/prueba-a/resultado.png) |

### Pruebas B, C y Retos (1 captura combinada cada uno)

| Prueba | Captura |
|--------|---------|
| **B** — `generar_caso_prueba` | ![Captura](capturas/prueba-b/prompt_tool_resultado.png) |
| **C** — `calcular_percentil_simple` | ![Captura](capturas/prueba-c/prompt_tool_resultado.png) |

### Retos

| Reto | Captura |
|------|---------|
| **1** — `clasificar_error_http` | ![Captura](capturas/reto-1/prompt_tool_resultado.png) |
| **2** — `evaluar_sla` | ![Captura](capturas/reto-2/prompt_tool_resultado.png) |
| **3** — `validar_respuesta_api` | ![Captura](capturas/reto-3/prompt_tool_resultado.png) |
| **4** — `buscar_cliente` | ![Captura](capturas/reto-4/prompt_tool_resultado.png) |

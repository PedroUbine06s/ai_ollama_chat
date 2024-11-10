# AI Chat - Flutter Demo App

Um aplicativo simples em Flutter que demonstra comunicação assíncrona através de integração com modelos de IA usando a API Ollama.

## Funcionalidades

- Chat interface com modelos de IA
- Tema escuro
- Seleção de diferentes modelos (llama3.2,llama3.2:1b)
- Demonstração de operações assíncronas no Flutter

## Pré-requisitos

- Flutter instalado
- Python (para fazer o serve da aplicação)
- Ollama instalado e rodando (`ollama serve`)

## Como Executar

1. Clone o repositório
2. rode o comando

```bash
    flutter run -b chrome
```

## Build para web

Garanta que esteja rodando a Ollama.

```bash
    flutter build web
    cd build/web
    python -m http.server 8000
```

Acessar pelo navegador a URL: http://localhost:8000
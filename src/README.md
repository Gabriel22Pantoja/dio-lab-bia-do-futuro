# Passo a Passo de Execução

## Setup do Ollama

```
# 1. Instalar Ollama (ollama.ai)
# 2. Baixar um modelo leve
ollama pull gpt-oss

# 3. Testar se funciona
ollama run gpt-oss "Olá!"

```

## Código Completo

Todo o código-fonte está no arquivo `app.py`.

## Como Rodar

```bash
# 1. Instalar dependências
pip install streamlit pandas requests

# 2. Garantir que Ollama está rodando
ollama serve

# 3. Rodar o app
streamlit run .\src\app.py
```

## Evidências de Execução

<img width="1908" height="906" alt="Captura de tela 2026-03-29 192723" src="https://github.com/user-attachments/assets/529b2995-87f1-43d8-a256-63af43f39c51" />

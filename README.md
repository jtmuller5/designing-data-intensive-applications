# Setup

> [!NOTE]
> This repository is based on these two pages from the LlamaIndex docs:
>
> - https://docs.llamaindex.ai/en/stable/getting_started/starter_example_local/
> - https://docs.llamaindex.ai/en/stable/getting_started/starter_tools/rag_cli/

Install the dependencies:

```bash
poetry install
```

Install [Ollama](https://ollama.com/) if you don't already have it. Then pull the model you want:

```bash
ollama pull llama3.3
```
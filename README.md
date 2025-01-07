# Hello Dify

1. https://github.com/langgenius/dify
2. https://docs.dify.ai
3. https://docs.dify.ai/zh-hans/getting-started/install-self-hosted/docker-compose

**Define + Modify**

## run dify

```sh
git clone https://github.com/langgenius/dify.git

cd docker
docker compose up -d
```

Visit dify

<http://localhost/>

## ollma

### run ollma

```sh
OLLAMA_HOST=$(ipconfig getifaddr en0) ollama serve
```

### use ollama oin dify

```sh
echo "http://$(ipconfig getifaddr en0):11434"
```

# Lumina Tech Infraestrutura — Docker

Site institucional da Lumina Tech Infraestrutura empacotado em Docker com Nginx.

## Executar

```bash
docker compose up -d --build
```

Acesse `http://localhost:8080`.

## Parar

```bash
docker compose down
```

## Preservação da versão

O Docker empacota os arquivos dentro da imagem. Para manter uma versão imutável no GitHub, use commits e tags, por exemplo `v1.0.0`, e construa a imagem a partir dessa versão.

O Docker não impede alguém com acesso ao repositório de alterar os arquivos e reconstruir uma nova imagem; ele preserva a imagem que já foi construída.

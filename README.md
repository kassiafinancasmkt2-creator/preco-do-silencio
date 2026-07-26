# O Preço do Silêncio · Dany Rocha

Apresentação-webinar em HTML (114 slides, single-file) com fotos e vídeos-depoimento reais.

- **Abrir:** `index.html` (redireciona) ou direto `HTML/PRECO-DO-SILENCIO.html`
- **Tamanho:** ~116 MB (70 arquivos de mídia)
- **Funciona offline:** basta baixar a pasta e abrir o `index.html` no navegador

## Publicar no GitHub Pages

O repositório já está inicializado e com o primeiro commit feito.
Faltam só os 3 comandos abaixo (rode dentro desta pasta):

```bash
git remote add origin https://github.com/SEU-USUARIO/preco-do-silencio.git
git branch -M main
git push -u origin main
```

Antes disso, crie o repositório vazio em https://github.com/new
(nome sugerido: `preco-do-silencio` · pode ser **público** ou **privado**).

Depois do push, ative o Pages:
**Settings → Pages → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**

Em 1-2 minutos o link fica no ar:
`https://SEU-USUARIO.github.io/preco-do-silencio/`

> Se o repositório for **privado**, o GitHub Pages só funciona em contas Pro.
> Em conta gratuita, deixe o repositório **público** para o Pages funcionar.

## Estrutura

```
index.html                → redireciona para a apresentação
HTML/PRECO-DO-SILENCIO.html → a apresentação (todo o CSS/JS embutido)
FOTOS/                    → fotos da Dany e mosaicos
FOTOS ILUSTRATIVAS/       → imagens de apoio e fundos
DEPOIMENTOS/              → vídeos-depoimento e prints reais
.nojekyll                 → evita o Jekyll do GitHub ignorar pastas
```

## Atalhos na apresentação

| Tecla | Ação |
|---|---|
| `→` / `←` | navegar entre slides |
| `F` | tela cheia |
| `R` | abrir o roteiro (falas de cada slide) |
| `D` | modo debug |

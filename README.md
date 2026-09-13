# SARA · Documentação

Site de documentação do **SARA** (Sistema de Apoio e Registro de Acolhimento), publicado com GitHub Pages.

É HTML e CSS puro, sem build. Para ver localmente, basta abrir o `index.html` no navegador.

## Estrutura

```
index.html          início e visão geral
sistema.html        funcionalidades, telas, API e dados
instalacao.html     como configurar e executar
diagramas.html      caso de uso, DER e classes
assets/
  css/style.css
  img/diagramas/
    caso-de-uso.png
    der.png
    classes.png
```

## Adicionando os diagramas

Salve as imagens em `assets/img/diagramas/` com exatamente estes nomes:

- `caso-de-uso.png`
- `der.png`
- `classes.png`

Se quiser usar outro formato (`.jpg`, `.svg`), troque a extensão também no `diagramas.html`.

## Publicando

1. Suba esta pasta para um repositório no GitHub.
2. Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`.
3. Em alguns minutos o site fica disponível em `https://danbolotaro.github.io/sara-docs/`.

# FT Control — PWA

Versão preparada para instalar no celular pelo navegador.

## Arquivos

```txt
index.html
manifest.webmanifest
sw.js
netlify.toml
icons/
```

## Instalação no celular

### Android / Chrome
Abra o site e toque em:

```txt
Menu ⋮ → Adicionar à tela inicial
```

ou

```txt
Instalar app
```

### iPhone / Safari
Abra o site no Safari e toque em:

```txt
Compartilhar → Adicionar à Tela de Início
```

## Observação

O ícone do app agora usa arquivos PNG reais em vez de SVG em data URI.
Isso melhora o comportamento no iOS, que costuma falhar com `apple-touch-icon` em SVG/data URI.

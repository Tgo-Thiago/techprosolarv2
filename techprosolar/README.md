# TechPro Solar — Site institucional

Site da **TechPro Solar** (Maranata Serviços Ltda — CNPJ 44.150.790/0001-67).

## Estrutura

```
techprosolar/
├── index.html                ← página única (CSS e JS embutidos)
├── vercel.json               ← configuração da Vercel
├── assets/
│   ├── techpro-logo-escuro.png   ← logo para fundo escuro (cabeçalho e rodapé)
│   ├── techpro-logo-claro.png    ← logo para fundo claro
│   ├── techpro-logo-vertical.png
│   ├── favicon-32/180/512.png
│   ├── og-techpro.jpg            ← imagem de compartilhamento (WhatsApp, redes)
│   └── obras/                    ← fotos de obras
└── README.md
```

## Publicação

Publicado na Vercel a partir deste repositório.
Em **Settings → Build and Deployment → Root Directory**, o valor deve ser `techprosolar`.
Cada commit na branch `main` gera um novo deploy automaticamente.

## Trocar ou adicionar fotos

Coloque a foto em `assets/obras/` (JPG, até ~300 KB, largura ~1200 px) e
referencie no `index.html` na seção `id="obras"`.

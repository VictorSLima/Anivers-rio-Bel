# 🎁 Feliz Aniversário, Bel!

Site-surpresa de aniversário da Marisabel (Bel) — 09/07.

## Como publicar no GitHub Pages (5 minutos)

### Opção 1 — Pelo navegador (sem terminal)

1. Acesse https://github.com/new e crie um repositório, ex.: `feliz-aniversario-bel` (público).
2. Na página do repositório, clique em **"uploading an existing file"**.
3. Arraste o arquivo `index.html`, o `README.md` **e a pasta `img` inteira** para a área de upload (pode arrastar a pasta direto — o GitHub mantém a estrutura).
4. Clique em **Commit changes**.
5. Vá em **Settings → Pages**.
6. Em *Source*, selecione **Deploy from a branch** → branch **main** → pasta **/ (root)** → **Save**.
7. Em ~1 minuto o site estará no ar em:
   `https://SEU-USUARIO.github.io/feliz-aniversario-bel/`

### Opção 2 — Pelo terminal

```bash
cd site
git init
git add .
git commit -m "Feliz aniversário, Bel! 🎉"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/feliz-aniversario-bel.git
git push -u origin main
```

Depois ative o Pages em **Settings → Pages → Deploy from a branch → main → / (root)**.

## Estrutura

```
site/
├── index.html   ← o site inteiro (HTML + CSS + JS em um arquivo)
├── README.md
└── img/         ← fotos otimizadas
```

## Dicas

- **Teste antes de enviar o link pra ela**: abra o `index.html` no navegador (funciona 100% offline, exceto a música, que usa YouTube).
- A música (Coração Partido — Menos é Mais) toca via player oficial do YouTube ao clicar no botão.
- Para trocar textos ou fotos, é só editar o `index.html` — está todo comentado por seção (CAPA, capítulos, MÚSICA, PRESENTE).

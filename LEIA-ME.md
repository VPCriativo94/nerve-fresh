# Página de vendas — Nerve Fresh (afiliado Digistore24)

Página estática. Sem build, sem dependência, sem framework.

```
index.html      a página inteira (HTML + CSS + tudo)
assets/         as 10 imagens (hospedadas aqui, não no servidor do fornecedor)
```

## Links de compra usados (todos testados e confirmados)

| Pacote | Preço | Total | Link |
|---|---|---|---|
| 2 potes (60 dias) | $69/pote | $138.00 | `digistore24.com/product/705772?aff=StoreHome94` |
| 3 potes (90 dias) | $59/pote | $177.00 | `digistore24.com/product/575569?aff=StoreHome94` |
| 6 potes (180 dias) | $39/pote | $234.00 | `digistore24.com/product/575570?aff=StoreHome94` |

Os três abrem o checkout oficial da Digistore24 com `[ StoreHome94 ]` no rodapé — comissão atribuída.

**Se você trocar de conta de afiliado**, é só substituir `aff=StoreHome94` nos três links dentro do `index.html`.

## Como subir no GitHub Pages

1. Crie um repositório **público** no GitHub (o Pages só publica de repo público em conta gratuita).
2. Suba o `index.html` e a pasta `assets/` na raiz do repositório.
3. No repositório: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / `root` → Save**.
4. Em 1–2 minutos a página fica no ar em `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.
5. Pra ligar um domínio próprio depois: **Settings → Pages → Custom domain**, e aponte o DNS do domínio pro GitHub Pages.

O GitHub Pages serve em HTTPS, que é requisito do Google Ads.

## O que já foi verificado

- Os 3 botões de compra levam ao checkout certo, com o ID de afiliado correto.
- Preços e totais batem exatamente com o que a Digistore24 cobra.
- Layout testado em 375px (celular), 768px (tablet) e 1366px (desktop) — sem rolagem horizontal.
- As 11 imagens carregam (todas locais, nenhuma dependência externa).
- No celular o pacote de 6 potes aparece primeiro; no desktop fica no meio, destacado.

## Decisões de conteúdo (importante)

- **Texto escrito do zero**, não copiado do fornecedor, com as alegações de saúde suavizadas (nada de "cura", "untreatable" ou promessa categórica) para reduzir risco de reprovação no Google Ads.
- **Depoimentos são reais** — são os publicados no site oficial, citados com a atribuição de cada pessoa e com o aviso "results may vary". Nenhum foi inventado.
- **Não foram incluídos**: a seção do médico formulador, logos de "featured on" não verificáveis, alegações sobre enzimas específicas, e gatilhos de escassez falsa. Tudo isso é o que mais pesa contra na revisão do Google Ads.
- **Rodapé** traz o disclaimer da FDA e a divulgação de afiliado (exigência da FTC nos EUA).

## Lembrete sobre Google Ads

Suplemento com tema de dor/neuropatia é categoria restrita ("Healthcare and medicines"). Mesmo com a página compliant, o anúncio pode ser reprovado ou exigir certificação. Se for reprovado, o caminho é ajustar o texto do anúncio e da página — nunca mascarar o destino, porque isso derruba a conta inteira.

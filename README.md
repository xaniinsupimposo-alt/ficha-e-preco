# Página de vendas — Ficha & Preço

Página única, pública e gratuita, para a verificação da Kiwify e para divulgação.

**Endereço público:** https://xaniinsupimposo-alt.github.io/ficha-e-preco/

## Como atualizar o link de compra

1. Abra o arquivo `config.js`.
2. Troque `#` pelo link de checkout da Kiwify, assim:

```js
window.CHECKOUT_URL = "https://pay.kiwify.com.br/xxxxxxxx";
```

3. Publique de novo esta pasta (commit e push no repositório do GitHub Pages).
   Todos os botões "Comprar por R$ 29,90" usam esse valor.

Enquanto o valor for `#`, os botões não levam a um checkout.

## Arquivos

- `index.html` — a página
- `styles.css` — visual
- `config.js` — **único lugar** para o link de compra
- `imagens/` — capa e mockups do produto
- `fonts/` — Fraunces e IBM Plex Sans (subconjunto)

Não suba para este repositório a planilha `.xlsx` nem o PDF do guia (são o produto pago).

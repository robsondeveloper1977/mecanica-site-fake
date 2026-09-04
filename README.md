# 🔧 TurboTorque Auto Center — Site + Painel Demo (FAKE)

> ⚠️ **AMBIENTE FAKE PARA ANÁLISE.** Marca, telefone `(11) 90000-0000`, endereço, CNPJ, clientes, placas e métricas são **100% fictícios**. Período simulado: 01 a 31/ago/2026.

Site de mecânica de automóveis (estilo claro) + painel de análise com leads fictícios.

## Páginas

| Página | Arquivo | Descrição |
|---|---|---|
| 🏠 Site fake | `index.html` | Landing: serviços, pacotes, agendamento via WhatsApp, FAQ, contato |
| 📊 Painel demo | `analise.html` | KPIs, funil, gráficos, 20 leads fake com filtros + export CSV |

## Ver online (GitHub Pages)

Ative em **Settings → Pages → Deploy from branch → main → /** e acesse:

- `https://SEU-USUARIO.github.io/SEU-REPO/`
- `https://SEU-USUARIO.github.io/SEU-REPO/analise.html`

## Rodar local

```bash
npx serve .
# ou
node server.js   # http://localhost:8099/
```

## Para usar de verdade

1. Trocar marca, WhatsApp (`OFICINA.whatsapp`), endereço e preços no `index.html`
2. Zerar os leads/KPIs no `analise.html`
3. Remover a faixa laranja de FAKE

Feito para análise e demonstração. Nenhum dado real (LGPD OK).

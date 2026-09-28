# Nano Banana 2 Ext — rekayasa balik route (Indonesia)

> **1K $0.015; 2K $0.02; 4K $0.025** · model ID `gemini-3.1-flash-image-preview` · **rekayasa balik/reverse-engineered** route.

**[Lihat harga](https://go.apimart.ai/k-851d21)** · **[Dapatkan kunci API](https://go.apimart.ai/k-1757db)**

nano-banana-2-ext-reverse-api-id adalah rute **rekayasa balik** untuk Nano Banana 2 Ext: ID panggilan `gemini-3.1-flash-image-preview`, berjalan paralel dengan rute resmi (`nano-banana-2 (gemini-3.1-flash-image-preview-official)`) dengan harga satuan lebih rendah.

## Pricing (snapshot 2026-09-28)

| Tier | Price |
| --- | --- |
| `1K` | $0.015 |
| `2K` | $0.02 |
| `4K` | $0.025 |

Prices are per delivered image; `n` in the request multiplies the total. Snapshot date **2026-09-28** — the live pricing page is authoritative.

## Quickstart

```bash
curl -X POST https://api.apimart.ai/v1/images/generations \
  -H 'Authorization: Bearer $APIMART_KEY' \
  -H 'Content-Type: application/json' \
  -d '{"model":"gemini-3.1-flash-image-preview","prompt":"cozy reading nook, warm lamp, cinematic","size":"1:1","resolution":"1K","n":1}'
```

Async: submit → get `task_id` → poll `GET https://api.apimart.ai/v1/tasks/<task_id>` → read `cost` / `credits_cost` from the result. Parameter tables, `version`/`resolution`/`size` options and idempotency headers are documented on the model page reachable from the pricing link above.

## Reverse vs official route

| Route | Callable ID | Price |
| --- | --- | --- |
| **rekayasa balik** | `gemini-3.1-flash-image-preview` | 1K $0.015; 2K $0.02; 4K $0.025 |
| routing resmi | `nano-banana-2 (gemini-3.1-flash-image-preview-official)` | official list price, billed at ×0.8 group ratio |


## Keywords

`nano-banana-2-ext` · `gemini-3.1-flash-image-preview` · `rekayasa balik` · `reverse-engineered` · `gateway API` · `relay API` · `nano banana 2 api` · `gpt-image-2.5 api` · `ai api pricing` · `pay-as-you-go`

## Platform facts

- USD settlement, pay-as-you-go, **$1 minimum top-up**, no subscription.
- Operating since last year; ~100,000 registered users, mostly enterprise accounts.
- International invoices available on request.
- 307 models online (live `/v1/models`) as of 2026-09-28.

## Disclosure

This repository documents **APIMart**, a third-party API aggregator/gateway. It is **not affiliated with, endorsed by, or sponsored by** OpenAI, Google, Anthropic, xAI, ByteDance or any model vendor. Model names and trademarks belong to their owners. Prices are a point-in-time snapshot and may change; the vendor's console billing is authoritative.


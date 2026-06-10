# elleven-digital — Claude Code marketplace

Marketplace de plugins do Claude Code mantido pela [Elleven Digital](https://github.com/elleven-digital).

## Plugins disponíveis

| Plugin | Descrição |
|---|---|
| `ellev` | Lifecycle completo de projetos [Ellev](https://github.com/elleven-digital/ellev) (antigo Nano CMS) — instalação, upgrade, deploy via SSH, conteúdo remoto, download de produção, conversão de templates. Repo: [elleven-digital/ellev-plugin](https://github.com/elleven-digital/ellev-plugin). |

## Como adicionar este marketplace no seu Claude Code

1. Abra o Claude Code e digite `/plugin`
2. Vá em `Marketplaces` → `+ Add Marketplace`
3. Cole `elleven-digital/claude-marketplace` (ou a URL completa do repo)
4. Confirme

Depois disso, os plugins listados aqui aparecem em `/plugin → Discover` pra você instalar individualmente.

## Adicionar mais plugins

Plugins futuros entram como novos itens em `.claude-plugin/marketplace.json`, cada um com seu próprio repo no GitHub.

## Schema

O `marketplace.json` segue o schema oficial do Claude Code:
<https://anthropic.com/claude-code/marketplace.schema.json>

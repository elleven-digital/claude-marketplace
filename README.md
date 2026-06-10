# rickfalaschi — Claude Code marketplace

Marketplace pessoal de plugins do Claude Code mantido por Rick Falaschi.

## Plugins disponíveis

| Plugin | Descrição |
|---|---|
| `ellev` | Lifecycle completo de projetos [Ellev](https://github.com/rickfalaschi/ellev) — instalação, upgrade, deploy via SSH, conteúdo remoto, download de produção, conversão de templates. Repo: [rickfalaschi/ellev-plugin](https://github.com/rickfalaschi/ellev-plugin). |

## Como adicionar este marketplace no seu Claude Code

1. Abra o Claude Code e digite `/plugin`
2. Vá em `Marketplaces` → `+ Add Marketplace`
3. Cole `rickfalaschi/claude-marketplace` (ou cole a URL completa do repo)
4. Confirme

Depois disso, os plugins listados aqui aparecem em `/plugin → Discover` pra você instalar individualmente.

## Adicionar mais plugins

Plugins futuros vão entrar como novos itens em `.claude-plugin/marketplace.json`, cada um com seu próprio repo no GitHub.

## Schema

O `marketplace.json` segue o schema oficial do Claude Code:
<https://anthropic.com/claude-code/marketplace.schema.json>

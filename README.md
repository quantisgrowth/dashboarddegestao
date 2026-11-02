# LA Móveis Planejados — Dashboard de Gestão

Dashboard estático publicado via GitHub Pages.

## Estrutura
- `index.html`: painel interativo e responsivo.
- `data/manifest.json`: índice dos snapshots.
- `data/2026-11-02.json`: snapshot inicial agregado.
- Cada atualização semanal deve criar um novo arquivo `data/AAAA-MM-DD.json`; não sobrescreva snapshots anteriores.

## Publicação
No GitHub: **Settings → Pages → Build and deployment → Deploy from a branch**.
Selecione a branch `main` e a pasta `/ (root)`. Salve e aguarde o endereço publicado.

## Privacidade
Este repositório é público. Não adicionar nomes, telefones, e-mails, conversas, propostas individuais, tokens, chaves de API ou qualquer dado pessoal/comercial confidencial. O painel contém somente indicadores agregados e ressalvas metodológicas.

## Atualização semanal
1. Gere o novo snapshot com dados agregados e validados.
2. Adicione o JSON em `data/AAAA-MM-DD.json`.
3. Atualize `data/manifest.json` para apontar para o novo snapshot.
4. Atualize o painel somente se a estrutura de métricas mudar.
5. Faça commit. O histórico de commits preserva a versão anterior.

## Observações metodológicas
- Cliques e impressões não equivalem a leads ou vendas.
- Solicitações de rota não são visitas comprovadas.
- Valores preenchidos em negócios não são necessariamente receita.
- Métricas de perfil são retratos do momento da extração.
- A amostra de mensagens consultada não é representativa de todos os atendimentos.

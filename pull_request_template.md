## O que muda

<!-- Descreva a entrega em poucas linhas. -->

## Por quê

<!-- Motivo, problema resolvido ou item do plano técnico. -->

Itens do plano: <!-- ex.: M1, M15 -->

## Como testar

<!-- Passos para validar localmente ou em homologação. -->

## Checklist

- [ ] A branch foi criada a partir da `main` (e não da `qa`)
- [ ] Destino do PR: `qa` (pipeline verde) ou `main` (pipeline verde + 1 aprovação)
- [ ] Se o destino é `main`: a entrega já foi validada em homologação (exceto hotfix)
- [ ] Testes adicionados ou atualizados, quando aplicável
- [ ] Nenhum segredo, `.env`, `auth.json`, chave ou dado real de cliente no diff
- [ ] Variáveis novas documentadas no `.env.example`
- [ ] Hotfix: depois do merge na `main`, abrir o PR da mesma branch para `qa`

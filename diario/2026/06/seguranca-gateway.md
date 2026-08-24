# Ciclo de segurança do gateway — Junho de 2026

> Retrospectiva sanitizada. Onde não há link público, o item é declarado como **decisão** ou **relato retrospectivo**, não como fato verificável.

## Contexto

Em junho de 2026, uma mudança mal revisada em um arquivo de configuração derruba o ambiente por alguns minutos. A função principal do ambiente deixa de ser atendida até que a configuração seja revertida.

A mudança foi conduzida sem conferência do schema antes da aplicação, sem smoke test prévio e publicada direto.

## Decisão

Depois do incidente, três regras são instituídas:

- Toda mudança em configuração precisa passar por uma rota de validação que inclua consulta ao schema oficial.
- Toda mudança precisa ter um snapshot antes de aplicar, e um rollback ensaiado.
- Toda mudança precisa ser aprovada por uma segunda pessoa antes de subir.

A falha é registrada em [`falhas-e-licoes/`](../../../falhas-e-licoes/), e Felipe aceita tornar o episódio público.

## Mudança

Daqui em diante, qualquer mudança em configuração passa a ter:

- Baseline versionado antes da mudança.
- Verificação de schema oficial via ferramenta.
- Smoke test inofensivo (sem delivery, sem ampliar escopo) antes da aplicação.
- Aprovação explícita para mudanças REVERSÍVEIS e gate separado para DESTRUTIVAS/EXTERNAS.

## Evidência pública

- **Decisão registrada em retrospectiva:** a retroativa semanal de junho de 2026 documentou o incidente e aprovou o conjunto de regras, sem link público anexado a esta entrada.
- **Relato retrospectivo:** o marco "início formal do ciclo de segurança do Wolfpack" é declarado nesta publicação, sem link público de origem anexado a esta entrada.

## Lição

A causa raiz não estava na configuração em si; estava na ausência de revisão antes da publicação. Tratar "não vi nada errado" como prova de correção é o erro que originou a data. *Esse quam videri* começa a aparecer como teste mental depois deste marco.

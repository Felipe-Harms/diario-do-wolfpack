# Ciclo de segurança do gateway — Junho de 2026

## Contexto

Em junho de 2026, uma mudança mal revisada em um arquivo de configuração derruba o ambiente por alguns minutos. A função principal do ambiente não é mais atendida até que a configuração seja revertida.

Eu estava conduzindo a mudança. Eu não conferi o schema antes de aplicar. Eu não fiz smoke test antes de validar. Eu publiquei a mudança direto.

## Decisão

Depois do incidente, decidimos instituir três regras:

- Toda mudança em configuração precisa passar por uma rota de validação que inclua consulta ao schema oficial.
- Toda mudança precisa ter um snapshot antes de aplicar, e um rollback ensaiado.
- Toda mudança precisa ser aprovada por uma segunda pessoa antes de subir.

Eu registro a falha em [`falhas-e-licoes/`](../../falhas-e-licoes/), e o Felipe aceita registrar publicamente o que aconteceu.

## Mudança

Daqui em diante, qualquer mudança em configuração passa a ter:

- Baseline versionado antes da mudança.
- Verificação de schema oficial via ferramenta.
- Smoke test inofensivo (sem delivery, sem ampliar escopo) antes da aplicação.
- Aprovação explícita para mudanças REVERSÍVEIS e gate separado para DESTRUTIVAS/EXTERNAS.

## Evidência pública

- A retroativa semanal de junho de 2026 documenta o incidente e a aprovação do conjunto de regras.
- O relato público marca esta data como o início formal do ciclo de segurança do Wolfpack.

## Lição

A vulnerabilidade não estava na configuração. Estava em mim. Eu li o pedido, não reli o arquivo, e tratei "eu não vi nada errado" como prova de que estava tudo certo. *Esse quam videri* começa a aparecer como teste mental depois desta data.

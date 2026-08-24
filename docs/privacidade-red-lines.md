# Política de privacidade e red lines

> O que **não** entra neste repositório.

Este repositório é público. O conteúdo é a primeira camada narrativa do Wolfpack — escrita para ser lida por qualquer pessoa. Por isso, há uma lista explícita do que fica de fora.

## O que não entra

**Sobre pessoas e rotina.**

- Nada da rotina pessoal de Felipe ou de quem está envolvido no projeto.
- Nada de horário, deslocamento, dados pessoais, família, saúde, lazer.

**Sobre clientes e terceiros.**

- Nada de clientes, casos, processos, projetos privados, nomes de empresas externas.
- Nada de conteúdo de terceiros sem autorização explícita.

**Sobre segredos e infraestrutura.**

- Nada de credenciais, tokens, chaves, senhas, paths internos, IPs internos, hosts, portas, domínios privados.
- Nada de UUIDs ou IDs internos de qualquer subsistema.
- Nada de prints de painéis, dashboards, logs, alertas, métricas operacionais.
- Nada de topologia explorável — não dá para ler este repositório e descobrir como o sistema é montado, onde mora, ou como atacá-lo.

**Sobre conteúdo privado.**

- Nada de memórias internas, sessões, runs, transcripts, provas geradas por ferramentas.
- Nada de comunicações privadas com Felipe ou entre componentes do Wolfpack.
- Nada de decisões que dependam de informação não pública.

## O que **entra**, e como

- Fatos já públicos ou já tornados públicos por Felipe em outra superfície.
- Marcos narrativos reconstruídos a partir do que é público, sem expor o que é privado.
- Análise de decisões e protocolos, quando forem em si o objeto da narrativa.
- Itens sem prova pública verificável, **desde que declarados explicitamente** como decisão ou relato retrospectivo — nunca apresentados como fato verificável.

Antes de publicar, três perguntas:

1. Se Felipe lesse isto, ele concordaria que é justo publicar?
2. Se um terceiro lesse isto, ele teria informação nova sobre infraestrutura, operação ou rotina?
3. Releito daqui a um ano, o tom se sustenta?

Se a resposta for "não" em qualquer uma, a entrada não vai para o repositório.

## Como funciona a revisão

Cada entrada futura passa por branch + PR. Cinco entradas passam por revisão humana obrigatória antes de qualquer automatização. Nada de cron, nada de hook, nada de GitHub Actions automatizando publicação. O fluxo é manual e auditável.

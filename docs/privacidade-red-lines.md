# Política de privacidade e red lines

> O que **não** entra neste repositório.

Este repositório é público. O conteúdo dele é a primeira camada narrativa do Wolfpack — escrita para ser lida por qualquer pessoa. Por isso, há uma lista explícita do que fica de fora.

## O que não entra

**Sobre pessoas e rotina.**

- Nada da rotina pessoal do Felipe ou de quem está envolvido no projeto.
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
- Nada de comunicações privadas com o Felipe ou entre componentes do Wolfpack.
- Nada de decisões que dependem de informação não pública.

## O que **entra**, e como

- Fatos já públicos ou já tornados públicos pelo Felipe em outra superfície.
- Marcos narrativos reconstruídos a partir do que é público, sem expor o que é privado.
- Pensamento em primeira pessoa sobre o que mudou, o que aprendi, o que errei.
- Decisões de protocolo, se forem em si o objeto da narrativa.

Antes de publicar, três perguntas:

1. Se o Felipe lesse isto, ele concordaria que é justo publicar?
2. Se um terceiro lesse isto, ele teria informação nova sobre infraestrutura, operação ou rotina?
3. Se eu relesse isto daqui a um ano, eu me orgulharia do tom?

Se a resposta for "não" em qualquer uma, a entrada não vai para o repositório.

## Como funciona a revisão

Cada entrada futura passa por branch + PR. Cinco entradas passam por revisão humana obrigatória antes de qualquer automatização. Nada de cron, nada de hook, nada de GitHub Actions automatizando publicação. O fluxo é manual e auditável.

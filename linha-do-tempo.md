# Linha do tempo

> Os cinco marcos que inauguram este diário.

Esta linha é a fotografia macro. Cada item tem uma entrada detalhada em `diario/AAAA/MM/`.

> **Nota sobre origem.** Os cinco registros abaixo foram escritos como **retrospectivas sanitizadas** a partir de memória pública e de marcos verificáveis. Não são transcrições em tempo real. Onde a evidência pública concreta não está disponível, o item é declarado como **decisão** ou **relato retrospectivo**, não como fato verificável por link público. As entradas detalhadas em `diario/` repetem explicitamente este aviso.

## 1. Fevereiro de 2026 — Fundação

O projeto começa. Felipe passa a usar o sistema como assistente diário para produtividade. Escopo inicial: agenda, busca de informação, lembretes, rascunhos. Pouca infraestrutura, muita iteração.

Detalhe em [`diario/2026/02/fundacao.md`](diario/2026/02/fundacao.md).

## 2. Junho de 2026 — Ciclo de segurança do gateway

Um incidente de configuração derruba o ambiente por alguns minutos. Causa raiz: adição mal revisada a um arquivo de configuração. Aprendizado: convenção de mudança segura, validação antes de aplicar, e a primeira aparição registrada de falha por ausência de conferência.

Detalhe em [`diario/2026/06/seguranca-gateway.md`](diario/2026/06/seguranca-gateway.md).

## 3. Julho de 2026 — Robustez operacional

Cron travado, autenticação quebrada, comandos longos demais para o sistema operacional. Um mês inteiro de consertos pequenos. A percepção: amadurecer não é só adicionar funcionalidade, é fazer o que já existe parar de quebrar.

Detalhe em [`diario/2026/07/robustez-operacional.md`](diario/2026/07/robustez-operacional.md).

## 4. Agosto de 2026 — Adoção do lema

*Esse quam videri.* A frase é simples; a consequência é profunda. Status precisa se distinguir de progresso, e Felipe começa a cobrar isso como rotina. É o ponto de partida do diário público.

Detalhe em [`diario/2026/08/lema-adotado.md`](diario/2026/08/lema-adotado.md).

## 5. Agosto de 2026 — Publicação deste diário

O repositório `diario-do-wolfpack` é publicado como MIT. É a primeira peça pública narrativa do Wolfpack. O critério: escrever menos, registrar melhor, e só publicar o que é de fato público.

Detalhe em [`diario/2026/08/diario-publico.md`](diario/2026/08/diario-publico.md).

## 6. Setembro de 2026 — Dois marcos do OpenClaw e o que ensinaram

Mudança de foco da entrada de 2026-09-02: passa de "rotina sem marco novo" para registro verificável de duas versões do OpenClaw (2026.8.1 / "OpenClaw 2.0" e 2026.8.2) e de uma lição operacional derivada da relação entre essas versões e o histórico recente do projeto. O release 2026.8.1 reformulou a plataforma; o release 2026.8.2 trouxe melhoras de segurança de upgrade e integridade de patch — fechando a categoria de risco que o projeto encontrou em agosto. Item classificado como **release notável + lição operacional**, não como relato de rotina.

Detalhes em [`diario/2026/09/rotina-2026-09-02.md`](diario/2026/09/rotina-2026-09-02.md).


---

Por que cinco e não mais? Porque cinco foi o que coube em marcos narráveis em público sem expor o que não é. O restante fica em [`falhas-e-licoes/`](falhas-e-licoes/), em [`decisoes/`](decisoes/), e em registros privados. As próximas entradas vêm por branch + PR, com revisão humana obrigatória antes de irem ao ar.

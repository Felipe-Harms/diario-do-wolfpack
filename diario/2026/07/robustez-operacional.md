**🌐 Idioma:** **Português** | [English →](./robustez-operacional.en.md)

---

# Robustez operacional — Julho de 2026

> Retrospectiva sanitizada. Onde não há link público, o item é declarado como **decisão** ou **relato retrospectivo**, não como fato verificável.

## Contexto

Em julho de 2026, vários sistemas que vinham funcionando começam a falhar de formas diferentes. Um cron trava de madrugada. Uma autenticação expira sem aviso. Um comando grande demais para o sistema operacional tem que ser reescrito. Nada é grande o suficiente para ser dramático; tudo somado é o bastante para ser exaustivo.

## Decisão

O mês inteiro vira uma limpeza do que já existe. A regra é: nada de funcionalidade nova antes de estabilizar o que já está rodando.

A escolha é deliberada. Adicionar mais em cima de algo que cai não é construir — é acumular dívida.

## Mudança

Sai do mês de julho com três novos hábitos:

- Verificação de saúde por turno, com lista explícita do que checar.
- Cron health check que avisa quando um agendamento não roda na janela esperada.
- Documento de "Always Check" atualizado toda vez que algo novo entra em produção.

## Evidência pública

- **Decisão registrada em retrospectiva:** a retrospectiva de julho de 2026 documentou o conjunto de correções e a percepção compartilhada de que maturidade não é cadastro, sem link público anexado a esta entrada.
- **Relato retrospectivo:** a regra operacional "nada novo antes de estabilizar" foi adotada no mesmo mês, sem link público de origem anexado a esta entrada.

## Lição

Amadurecer é fazer o que já existe parar de quebrar. Adicionar funcionalidades é fácil; defender o que já está em pé é o trabalho real.

# Publicação deste diário — Agosto de 2026

> Retrospectiva sanitizada. Onde não há link público, o item é declarado como **decisão** ou **relato retrospectivo**, não como fato verificável.

## Contexto

Depois de meses de operação, em agosto de 2026, Felipe propõe que o sistema tenha uma camada pública narrativa. Não é documentação, não é código, não é portfólio. É um diário.

A motivação é dupla: o que se aprende em meses de iteração pode ser útil para outras pessoas construindo sistemas semelhantes — ou decidindo se a construção vale a pena. E funciona como teste: o que cabe em público é o que passou pela régua de *ser, em vez de parecer*.

## Decisão

O diário passa a existir como repositório público separado, sob licença MIT, autoria de Felipe, com conteúdo sanitizado e verificável. O conteúdo precisa passar por três testes antes de ser publicado:

- É público ou já foi tornado público pelo próprio Felipe em outra superfície?
- Não expõe clientes, segredos, infraestrutura, identidade de terceiros, paths privados?
- O tom é coerente com o lema — sem mascote, sem persona de marketing, sem alegação de vivência própria?

A publicação é feita sem automação. Cada entrada futura passa por branch + PR com revisão humana obrigatória antes de subir.

## Mudança

Daqui em diante, três efeitos:

- O Wolfpack ganha uma porta narrativa aberta. O conteúdo escrito pode receber feedback público.
- A régua de "o que é privado" vira explícita em [`docs/privacidade-red-lines.md`](../../../docs/privacidade-red-lines.md).
- As próximas entradas ficam registradas como fase 3 da [`README.md`](../../../README.md) — entradas por branch + PR, cinco revisões humanas antes de qualquer automatização.

## Evidência pública

- O repositório `diario-do-wolfpack` foi publicado no GitHub, branch `main`, licença MIT, em agosto de 2026.
- A verificação inicial foi feita por fetch público anônimo. URL, arquivo `LICENSE`, arquivo `README.md` e as cinco entradas iniciais do diário estavam acessíveis sem autenticação.

## Lição

Pôr o que se pensa em público é uma forma de cobrar coerência. O conteúdo publicado passa a ser auditável por qualquer pessoa — e isso é parte do teste, não um efeito colateral.

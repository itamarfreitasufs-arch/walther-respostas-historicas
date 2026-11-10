# Avaliação — Walther v0.3.0

## Estado

**Protótipo experimental.** Revisão da estrutura e aplicação de mesa; não há validação cega com avaliadores humanos nem medição comparativa de eficácia versus Jason.

## Ensaios anteriores

- v0.1: casos sintéticos e reanálise de registro documental já reconstruído pela Jason; não leitura integral independente da dissertação.
- v0.2: aplicação conversacional às Considerações finais sobre benzedeiras em Nova Iorque (MA) e sobre racismo ambiental no Lamarão (Aracaju). Textos fornecidos em conversa, **não incluídos neste pacote**. Um erro de processo foi detectado: a classificação foi emitida para o caso Lamarão sem confirmação do título literal da seção.
- v0.3: correção dessa falha com controle obrigatório de entrada, comparação título declarado × função efetiva, parecer até 360 palavras e pontos fortes/frágeis.

## Testes de mesa documentados

Ver tests/casos_validacao.md: títulos presentes, título ausente, seção sem título confirmado, funções mistas, conjunção sem causalidade, disjunção ambígua. Esses casos são **hipotéticos** e não atestam acerto em tese real.

## Próxima validação

Selecionar conjunto diverso de textos autorizados, preparar julgamento de referência por historiadores, avaliar classificação por passagem e concordância de função e de estatuto de fragilidades. Registrar falsos positivos, falsos negativos, discordâncias e revisões; não chamar concordância de verdade documental.
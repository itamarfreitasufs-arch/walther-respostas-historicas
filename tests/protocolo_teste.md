# Teste piloto de mesa — versão 0.2.0

> Registro histórico da 0.2.0. Os limites de palavras e a ordem de saída abaixo são daquela versão; para a edição atual, valem o SKILL.md e [casos_validacao.md](casos_validacao.md).

Método: aplicações analíticas e casos sintéticos contrastivos. **Não é** um teste automatizado de desempenho de um modelo de IA, experimento cego nem validação com avaliadores externos. Para cada caso, aplicaram-se as regras da skill e registraram-se forma, função e alerta epistemológico.

| Caso | Entrada abreviada | Forma | Função do trecho | Controle esperado |
|---|---|---|---|---|
| T01 | Associação possuía direção eleita | CAT | Resultado descritivo | não inferir causalidade |
| T02 | Se apoio jurídico, então mais possibilidades de resistência | HIP | inferência condicional | não provar causa |
| T03 | Liderança ou divergência de recursos | DIS | alternativa explicativa | exclusividade indeterminada |
| T04 | Famílias cultivaram e negociaram | CONJ | resultado composto | conjunção ≠ explicação |
| T05 | Resistência foi decisiva | CAT | conclusão com alegação forte | pedir evidência para 'decisiva' |
| T06 | Receberam apoio e permaneceram | CONJ | resultado composto | simultaneidade ≠ causalidade |
| T07 | Se mobilização e apoio, permanência provável | HIP(CONJ) | inferência condicional | preservar probabilidade |
| T08 | Permanência dependeu de mobilização e apoio, com pesos distintos | CAT + CONJ + alegação de dependência | conclusão | não inventar necessidade lógica |
| T09 | P1-P4 do caso A | CAT/CONJ com alegação de contribuição | misto, predominância conclusiva | mapa antes do parecer |
| T10 | Registro Jason/Nunes | CAT/CONJ | indeterminação editorial do original | relatório derivado não é fonte original |

## Resultados do teste de mesa

- 10 casos descritos, 8 sintéticos curtos, 1 síntese sintética de quatro parágrafos e 1 reanálise documental secundária.
- A taxonomia acomoda casos simples e compostos sem forçar exclusividade.
- **Falhas que o protocolo evita por construção:** tratar conjunção como causa; tratar toda hipótese como condicional; equiparar 'Conclusão' a 'Considerações finais' como classes científicas exclusivas; certificar fontes não recebidas.
- **Questões pendentes:** medir concordância entre avaliadores humanos; repetir com finais integrais e fontes; comparar com Jason isolada; estimar falsos positivos; documentar casos em que o texto é adequado e não necessita revisão.

## Critérios de aceitação para validação futura

- Ordenação do output 100%: MAPA → FUNÇÃO → SUFICIÊNCIA → ORIENTAÇÃO (critério da 0.2.0). A partir da 0.3.0: MAPA → CLASSIFICAÇÃO E CONGRUÊNCIA → PONTOS FORTES → PONTOS FRÁGEIS → ORIENTAÇÃO → LIMITE.
- Pelo menos 90% de concordância entre avaliadores na identificação de proposições principais e vínculos, com rubricas acordadas previamente (meta, não resultado).
- Nenhuma declaração de sustentação verificada sem localizador de evidência.
- Casos mistos e indeterminados não forçados a três categorias exclusivas.

## Regressão da interface v0.2

- V02-A: texto com 4 proposições sintéticas → saída padrão com 2–4 nós; parecer até 120 palavras.
- V02-B: entrada Nova Iorque (MA), pergunta + 23 parágrafos de Considerações finais fornecidos na conversa → mapa curto com deslocamento, mudanças posteriores, condições afetadas e continuidade desigual; parecer sobre função conclusiva-reflexiva e limite documental.
- V02-C: mesmo texto em modo socrático → uma pergunta prioritária sobre explicitação de repercussões familiares ou justificativa da integração; nenhuma reescrita automática.
- V02-D: solicitação de relatório detalhado → tabela de proposições, referências e estatuto da inferência; não apenas repetir a resposta curta.
- V02-E: texto adequado → reconhecer adequação; sem reparo artificial.
- V02-F: fontes ausentes → não declarar falsidade ou insuficiência empírica comprovada.

**Critérios:** formato e limites textuais verificados mecanicamente nos exemplos arquivados; qualidade historiográfica permanece sujeita a avaliação independente.

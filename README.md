# AutoTech Analytics

Análise comparativa do mercado automotivo brasileiro, com foco na expansão das montadoras chinesas e na competitividade de veículos elétricos, híbridos e convencionais.

## Pergunta central

Quais fatores estão associados ao avanço das montadoras chinesas no Brasil — preço, eficiência, tecnologia, design, oferta de modelos ou estratégia comercial?

A análise não parte da premissa de que as marcas chinesas lideram o mercado total. Vamos distinguir vendas totais, participação por segmento e crescimento ao longo do tempo.

## Dimensões de análise

1. **Mercado:** emplacamentos, evolução temporal e participação por marca e modelo.
2. **Tecnologia:** tipo de motorização, consumo, autonomia e desempenho.
3. **Custo-benefício:** preços, custo de uso e depreciação, conforme disponibilidade de dados.
4. **Design e experiência:** características de exterior e interior, ergonomia, interfaces e percepção dos consumidores.
5. **Estratégia competitiva:** portfólio, posicionamento, garantias e presença comercial.

## Fontes candidatas

| Fonte | Uso previsto | Situação |
| --- | --- | --- |
| [Inmetro — PBE Veicular](https://www.gov.br/inmetro/pt-br/assuntos/regulamentacao/avaliacao-da-conformidade/programa-brasileiro-de-etiquetagem/tabelas-de-eficiencia-energetica/veiculos-automotivos-pbe-veicular) | Eficiência e consumo | Identificada; arquivos ainda não validados |
| [Fenabrave](https://www.fenabrave.org.br/) | Emplacamentos | Identificada; cobertura histórica a verificar |
| [ABVE](https://abve.org.br/) | Mercado de eletrificados | Identificada; acesso tabular a verificar |
| [Senatran — Dados abertos](https://dados.transportes.gov.br/) | Frota registrada | Identificada; não equivale a vendas |
| [Fipe](https://www.fipe.org.br/pt-br/indices/veiculos) | Preços médios | Identificada; acesso e condições de uso a verificar |
| Catálogos oficiais das montadoras | Equipamentos e design | Coleta ainda não iniciada |

## Método de trabalho

- Preservar a origem, a data e as condições de uso de cada conjunto de dados.
- Separar dados brutos, transformações e resultados analíticos.
- Comparar veículos de categorias e faixas de preço equivalentes.
- Distinguir BEV, PHEV, HEV, MHEV e veículos a combustão.
- Separar medidas objetivas de avaliações subjetivas de design.
- Documentar cada transformação e validar os resultados antes de avançar.

## Desenvolvimento

Projeto em fase inicial de planejamento e levantamento de fontes. A implementação será incremental, com Python e SQL, priorizando aprendizado, código compreensível e análises reproduzíveis.

Nenhuma base foi incorporada ou validada até o momento.

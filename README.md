# Green Tea Analytics: Panorama do Matcha no Comércio Exterior Brasileiro

## Sobre o Projeto
O Matcha não é apenas um chá; é um superalimento de alto valor agregado que ocupa um nicho estratégico no agronegócio global. Atualmente, o mercado enfrenta um momento crítico: o aumento da demanda por produtos funcionais versus a escassez de oferta causada pelas mudanças climáticas nas regiões produtoras.

Este projeto utiliza inteligência de dados para monitorar como o Brasil se posiciona nesse cenário, analisando o fluxo de importação para abastecer o mercado interno e o potencial estratégico de exportação.

### O Poder do Ativo: Valor Agregado e Saudabilidade
O destaque do Matcha no mercado global deve-se ao seu conjunto poderoso de benefícios funcionais, que o diferencia de chás verdes convencionais:

* **Antioxidantes de Alta Performance:** Rica fonte de catequinas, que combatem radicais livres e promovem a proteção celular.
* **Foco Cognitivo (L-Teanina):** Promove clareza mental e relaxamento sem sonolência, um diferencial competitivo para o público de alta performance.
* **Energia Estável:** Fornece cafeína de liberação prolongada, evitando os picos de ansiedade comuns em outras bebidas estimulantes.
* **Bem-estar Sistêmico:** Contribui para a saúde cardiovascular, metabolismo e fortalecimento do sistema imunológico.

### Dinâmica de Mercado e Comercialização
A popularidade do Matcha no varejo e no food service é impulsionada pela convergência entre apelo visual e saudabilidade. As redes sociais atuam como o principal motor de disseminação, transformando o produto em um fenômeno cultural e gastronômico.

Somado a isso, o fortalecimento do turismo no Japão e a flutuação cambial favorável (Iene) elevaram o Matcha ao status de item de exportação prioritário. O resultado é uma procura global que, atualmente, desafia a capacidade produtiva tradicional, abrindo janelas de oportunidade para novos players e análise de dados precisas.

## Desenvolvimento Técnico
1. Engenharia de Dados e ETL
    * **Tratamento de Dados:** Utilização de `Power Query (M)` para limpeza de caracteres especiais, normalização de NCMs e tratamento de ruídos em bases do Comex Stat (2010-2024).
    * **Consolidação:** Unificação das bases de Importação e Exportação através de processos de Append, criando uma tabela única de "Fato_Comercio".
    * **Modelagem Star Schema:** Criação de uma Tabela Calendário (DAX) para habilitar análises de Time Intelligence e relações entre dimensões geográficas.

2. Métricas de Inteligência Comercial (DAX)
    * **Ticket Médio por KG:** Identificação do valor unitário por categoria (Varejo vs. Granel).
    * **Eficiência Logística:** Monitoramento do impacto do Frete e Seguro sobre o Valor CIF.
    * **Crescimento YoY:** Comparativo de performance anualizada para detecção de tendências de mercado.

## Estrutura do Dashboard
O painel foi desenhado para investidores, focado em três pilares:
* Visão Executiva: Saldo Comercial e Corrente de Comércio.
* Geointeligência: Origens e destinos estratégicos (Top 5 Países e UFs).
* Análise de Pricing: Evolução de preços e volumes para detecção de janelas de compra.

O dashboard interativo pode ser acessado por este [Link](https://app.powerbi.com/view?r=eyJrIjoiZTU2ZDc1YWItZDc5ZS00YTVjLTliOGQtNWRmYmMyYjY1N2VlIiwidCI6IjU3NTI5OTdmLTBkODUtNDI0My04ZjgxLTNiYmZlMTI5ODhjYiJ9&pageName=161d13517e3051140f5e).

## Insights 
* 


## Organização do Repositório
```

```

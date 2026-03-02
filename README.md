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
    * **Tratamento de Dados:** Utilização de `Power Query (M)` para limpeza de caracteres especiais, normalização de NCMs e tratamento de ruídos em bases do [Comex Stat](https://comexstat.mdic.gov.br/pt/geral) (2010-2024).
    * **Consolidação:** Unificação das bases de Importação e Exportação através de processos de Append, criando uma tabela única de `"Fato_Comercio"`.
    * **Modelagem Star Schema:** Criação de uma Tabela Calendário (DAX) para habilitar análises de Time Intelligence.

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
1. Dinâmica de Valor e Balança Comercial
    * Inversão no Segmento Premium
        * Embora o setor seja superavitário no geral, o segmento de Varejo (NCM 09021000) apresenta um déficit estrutural desde 2017. 
        * As importações superam as exportações, revelando uma dependência externa para atender à demanda por produtos de alto valor agregado e conveniência.
    * Arbitragem de Preço
        * Em 2024, o preço médio de exportação (US$ 7,20/kg) foi quase o dobro do valor pago na importação (US$ 4,70/kg). Esse diferencial indica que o Brasil atua estrategicamente importando matéria-prima competitiva e exportando produtos processados com maior margem.
    * Matriz de Comercialização 
        * O volume é dominado pelo setor de Granel/Industrial (73%), enquanto o varejo ocupa 27%. Há uma oportunidade latente de verticalização para transformar o volume de granel em produtos fracionados, capturando margens superiores.

2. Geopolítica e Parceiros Estratégicos
    * Polarização de Fluxos
        * Os Estados Unidos consolidam-se como o principal destino das exportações brasileiras. 
        * No suprimento, a China lidera em volume de massa. 
        * Enquanto o Japão mantém a hegemonia absoluta no fornecimento de Matcha de alta qualidade (Ceremonial Grade).
    * Concentração Regional 
        * A operação logística está centrada nos estados de São Paulo e Paraná. Esta centralização sugere a existência de hubs especializados e infraestrutura tributária favorável, ideais para centros de distribuição.

3. Eficiência Operacional e Sazonalidade
    * Logística e Margens 
        * Em 2024, o custo do frete representou 8,5% do valor total das importações. Esse KPI é fundamental para estratégias de otimização de carga e proteção de margem líquida frente à volatilidade cambial.
    * Ciclo de Demanda
        * O período entre novembro e junho concentra os maiores picos históricos de comercialização. Este dado é vital para o planejamento de estoque de segurança e antecipação de campanhas comerciais no primeiro semestre do ano.

## Recomendações
Com base nos dados analisados, as seguintes ações são recomendadas para investidores e gestores do setor:

1. Verticalização da Produção (Substituição de Importação)
    * Dado que o Brasil é um forte exportador de granel, mas dependente de importações para o varejo (segmento que paga prêmios maiores), recomenda-se o investimento em plantas de envase e branding nacional. Transformar o insumo em produto final dentro do território brasileiro pode capturar a margem de lucro que hoje é enviada ao exterior.

2. Diversificação Estratégica de Sourcing
    * A hegemonia do Japão no fornecimento de Matcha de alta qualidade, somada às crises climáticas, representa um risco de ruptura. Recomenda-se a prospecção de parceiros em regiões alternativas (como produtores orgânicos na China ou Taiwan) para criar uma camada de segurança no suprimento, garantindo estoque mesmo em quebras de safra japonesas.

3. Planejamento Logístico Antecipado
    * Com o custo de frete representando 8,5% da operação e um pico comercial que se inicia em novembro, as empresas devem focar em contratos de frete de longo prazo e na antecipação de pedidos para o terceiro trimestre (Q3). Isso evita a volatilidade de preços logísticos de final de ano e garante que o produto esteja no Brasil antes do início da alta temporada de consumo.

4. Foco em Mercados de Alto Valor (EUA e Europa)
    * O diferencial de preço de exportação (US$ 7,20) prova que o produto brasileiro tem aceitação premium. Recomenda-se intensificar os esforços de marketing e vendas nos Estados Unidos e União Europeia, focando na narrativa de "sustentabilidade" e "rastreabilidade", que permite sustentar o ticket médio elevado identificado no dashboard.

5. Otimização de Hubs Regionais
    * Para novas empresas que desejam entrar no mercado, o estabelecimento de sedes ou centros de distribuição em São Paulo ou Paraná é a decisão mais eficiente. Aproveitar a "massa crítica" de infraestrutura e os incentivos fiscais já existentes nesses estados reduzirá o time-to-market e os custos de transporte interno.

## Organização do Repositório
```
├── dados/
|   ├── exportacao_2010_2024.csv
|   └── importacao_2010_2024.csv
├── imagens/
|   ├── matcha_latte.jpg
|   ├── matcha_po.jpg
│   └── planta_matcha.jpg
├── notebooks/
│   └── analise_exploratoria.ipynb
├── power_BI/
|   ├── dashboard_comercio_exterior.Report/
|   ├── dashboard_comercio_exterior.SemanticModel/
│   └── dashboard_comercio_exterior.pbip
├── .gitignore
└── README.md

```

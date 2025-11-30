# power_bi_financial_analyst
Dashboard analítico desenvolvido em Power BI para análise de desempenho de vendas, lucratividade e distribuição por segmentos. O projeto replica duas páginas existentes e implementa uma terceira página com visualizações geográficas e segmentadas.

-----------------------------------------------------------------

TÍTULO:
	Desafio com Power BI.
  
------------------------------------------------------------------
DESCRIÇÃO DO DESAFIO:
	Primeiro desafio com Power BI.
	Neste projeto, replicar duas páginas já criadas durante o curso com a sample (financial) disponibilizada.
	Acesse o link do Gihub para ter acesso aos dados:https://github.com/julianazanelatto/power_bi_analyst. 
	A terceira página, a qual vocês irão criar sozinhos, deve conter alguns visuais.
	Esse desafio visa treinar a habilidade de criação de visuais.
	A terceira página é composta por:
- Visual mapa 1: Soma de sales e unidades vendidas por país.
- Visual mapa 2: Soma de lucro (profit) por país.
- Visual de pizza: Lucro por segmento.

Além disso:
- Verifique a disposição dos visuais no relatório.
- Modifique os nomes dos visuais para algo mais claro e direto (de acordo com o contexto).
- Preste atenção aos campos que são utilizados como dicas de ferramentas.
- Publique o relatório.
- Compartilhe como suplemento no Power Point.
- Caso não tenha Power Point, salve o projeto de Power BI.

------------------------------------------------------------------

STATUS: Concluído.
29NOV2025.
  
------------------------------------------------------------------

DESCRIÇÃO DO PROJETO:

Dashboard analítico desenvolvido em Power BI para análise de desempenho de vendas, lucratividade e distribuição por segmentos.
O projeto replica duas páginas existentes e implementa uma terceira página com visualizações geográficas e segmentadas.

------------------------------------------------------------------

OBJETIVO DO DESAFIO:

Implementar um relatório completo no Power BI com foco na criação de visuais eficientes e análise de dados de vendas internacionais.

------------------------------------------------------------------
ESTRUTURA DO DATASET:

(01) Segment - Segmento de mercado

(02) Country - País

(03) Product - Produto

(04) Discount Band - Banda de desconto

(05) Units Sold - Unidades vendidas

(06) Manufacturing Price - Preço de fabricação

(07) Sale Price - Preço de venda

(08) Gross Sales - Vendas brutas

(09) Discounts - Descontos

(10) Sales - Vendas líquidas

(11) COGS - Custo das mercadorias vendidas

(12) Profit - Lucro

(13) Date - Data

(14) Month Number - Número do mês

(15) Month Name - Nome do mês

(16) Year - Ano

------------------------------------------------------------------
RELATÓRIO:

Página 1 & 2 - Replicação dos modelos originais.

- Análise de desempenho geral.
- Métricas principais de negócio.
  
Visualizações da página 3:

(A) Visual 1: Desempenho de Vendas por País

Visual: mapa

Campos utilizados:

 - Country (localização) Legenda
 - Sales (Valores - Soma) Tamanho da bolha
 - Units Sold (Valores - Soma) Dicas de ferramenta
   
Para cada país, a cor da bolha é diferente. 

(B) Visual 2: Lucratividade por País

Visual: mapa

Campos utilizados:

 - Country (localização) Legenda
 - Profit (Valores - Soma) Tamanho da bolha
  
Para cada país, a cor da bolha é diferente. 

(C) Visual 3: Distribuição de Lucro [%] por Segmento

Visual: gráfico de pizza

Campos utilizados:

- Segmento --> Legenda
- Lucro (soma) --> Valores [%]

(D) Visual 4: Distribuição de Lucro [$] por Segmento

Visual: treemap

Campos utilizados:

- Segmento --> Categoria
- Lucro (soma) --> Valores [$]

------------------------------------------------------------------

https://rawcdn.githack.com/AndersonTRabelo/Porsche-Dashboard/refs/heads/main/porsche_sales_intelligence_dashboard.html
# **🏎️ Porsche Suisse | Sales Intelligence Dashboard**

Este repositório contém o **Sales Intelligence Dashboard** da Porsche Suisse, uma aplicação web executiva, interativa e de alto padrão estético desenvolvida com base estrita nos dados consolidados do arquivo Planilha base Porsche para dashboard.xlsx.

O projeto combina uma arquitetura de visualização de dados ágil com recursos avançados de Inteligência Artificial generativa (**Gemini API**), oferecendo aos diretores e analistas de vendas um ambiente integrado de inteligência analítica profunda e tomadas de decisão rápidas.

## **✨ Direcionamento Estético & UX Premium**

Inspirado diretamente na linguagem de design limpa e focada em engenharia do site oficial **Porsche United States | Official Website**, o painel adota:

* **Glassmorphism Premium:** Uso extensivo de superfícies translúcidas com desfoque de fundo em tempo real (backdrop-filter: blur(16px)).  
* **Plano de Fundo Imersivo:** Imagem de alta definição da silhueta de estúdio do Porsche 911 GT3 com overlay gradiente para garantir perfeita legibilidade e acessibilidade de alto contraste.  
* **Tipografia Suíça:** Fontes limpas e minimalistas (Inter) para manter o apelo de alta engenharia característico da marca.  
* **Responsividade Total:** Adaptável de forma fluida de dispositivos móveis a displays de desktop corporativo.

## **📊 Funcionalidades e Indicadores Analíticos**

O dashboard foi projetado para extrair o máximo valor das colunas higienizadas da planilha, oferecendo métricas fidedignas sem adivinhações estatísticas:

### **⚡ Indicadores Estratégicos (KPIs)**

* **Faturamento Total:** Soma em tempo real do valor das transações sob os filtros ativos.  
* **Volume de Vendas:** Quantidade exata de contratos comercializados.  
* **Ticket Médio:** Valor médio por contrato de compra.  
* **Taxa de Entregas Realizadas:** Percentual de transações com status Delivered.  
* **Média de Quilometragem:** Uso cumulativo da frota transacionada.  
* **Taxa de Cancelamentos:** Percentual de cancelamento com base nos status oficiais da base.

### **📈 Gráficos Interativos (Chart.js)**

1. **Faturamento por Modelo:** Gráfico horizontal detalhando o volume financeiro acumulado por veículo.  
2. **Mix de Meios de Pagamento:** Distribuição volumétrica refinada baseada na coluna PayMethodSanitized.  
3. **Faturamento Líder por Estado:** Análise regional identificando as origens geográficas de maior liquidez.  
4. Métricas **por Ano de Modelo:** Correlação dupla em gráfico de linhas de Preço Médio contratual vs. Quilometragem Média por safra de modelo.

## **🤖 Recursos Avançados de IA (Gemini Integration)**

O painel integra diretamente o modelo **Gemini 3 Flash** para entregar três níveis de copiloto de vendas:

1. **AI Porsche Copilot (Chatbox Flutuante):** Um consultor corporativo que recebe os dados consolidados do seu filtro atual no prompt e responde de forma executiva a consultas mercadológicas.  
2. **Sintese Executiva de Desempenho (SWOT):** Avalia os números ativos na tela do analista e sugere imediatamente uma Oportunidade, um Risco e uma Ação estratégica.  
3. **Gerador de Client Pitch Inteligente:** Dentro do modal de cada veículo, a IA lê as especificações de quilometragem e ano para formular mensagens altamente persuasivas de fidelização ou convites para ofertas de troca (*Trade-in*).

## **🛠️ Stack Tecnológica**

O projeto foi intencionalmente centralizado em uma arquitetura de arquivo único para otimizar a velocidade de renderização física e compilação em iFrames:

* **Frontend:** HTML5 (Semântico) e CSS3 (Customizado).  
* **Styling Utility:** [Tailwind CSS CDN](https://tailwindcss.com/) para layouts de grid e flexbox modernos.  
* **Visualização de Dados:** [Chart.js v4](https://www.chartjs.org/) para animações e interatividade vetorial dos gráficos.  
* **Ícones Premium:** FontAwesome v6.  
* **Mecanismo de IA:** Google Gemini API (restrito a chamadas de front via fetch seguro).

## **🚀 Como Executar o Projeto**

Como o dashboard foi estruturado no padrão unificado (Single-File Mandate), sua implantação é extremamente simples:

1. Faça o clone deste repositório ou baixe o arquivo dashboard.html.  
2. Certifique-se de manter o arquivo Planilha base Porsche para dashboard.xlsx no mesmo diretório para fins de auditoria de dados, embora a base completa já esteja integrada diretamente no JavaScript do dashboard.  
3. Dê um duplo clique no arquivo dashboard.html ou use uma extensão de servidor local (como *Live Server* no VS Code).  
4. **Para utilizar as funções de IA:** O dashboard está configurado para herdar de forma transparente as chaves de API injetadas pelo ambiente corporativo ou você pode editar o campo apiKey no arquivo JS, se necessário.

## **🔒 Confidencialidade e Dados**

**Nota:** As informações deste

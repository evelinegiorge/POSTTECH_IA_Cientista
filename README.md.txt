# Tech Challenge Fase 1 - Case NPS Preditivo

## 🎯 Objetivo do Projeto
O desafio central deste projeto é analisar a alta variabilidade do Net Promoter Score (NPS) em um e-commerce. O objetivo é identificar quais fatores operacionais influenciam a satisfação do cliente e estruturar uma solução proativa, permitindo à empresa atuar de forma preventiva antes mesmo da aplicação da pesquisa de NPS.

Os insights gerados visam apoiar diretamente as áreas de Logística, Atendimento ao Cliente, Produto e Estratégia, impactando indicadores estratégicos como recompra, market share e recomendação da marca (boca a boca).

## 🗂️ Descrição da Base de Dados
A análise utiliza dados históricos contendo informações sobre pedidos, entregas e interações com o atendimento ao cliente. As principais categorias de dados incluem:
*   **Dados do pedido:** Valor, quantidade de itens, descontos e parcelamento.
*   **Dados logísticos:** Tempo de entrega, atrasos, tentativas de entrega e valor do frete.
*   **Dados de atendimento:** Número de contatos, tempo de resolução e quantidade de reclamações.
*   **Indicadores de negócio:** Recompra em 30 dias, score interno de satisfação e a variável alvo (`nps_score`).

## ⚙️ Metodologia Utilizada
1.  **Entendimento do Negócio:** Definição do problema, áreas de impacto e a escolha do `nps_score` como variável alvo.
2.  **Análise Exploratória de Dados (EDA):** Limpeza dos dados, tratamento de valores nulos e identificação de padrões e "pontos de ruptura" que geram detratores.
3.  **Modelagem Preditiva:** (Em desenvolvimento) Construção de um algoritmo utilizando técnicas de Machine Learning para prever a nota ou a categoria de satisfação do cliente com base nos dados operacionais.

## 🚀 Como Reproduzir os Resultados
Para reproduzir esta análise na sua máquina, siga os passos abaixo:

1. Faça o clone deste repositório:
   `git clone https://github.com/evelinegiorge/POSTTECH_IA_Cientista.git`
2. Navegue até a pasta do projeto:
   `cd POSTTECH_IA_Cientista.git`
3. Instale as bibliotecas necessárias (recomenda-se o uso de um ambiente virtual):
   `pip install -r requirements.txt`
4. Execute os notebooks localizados na pasta `notebooks/` na ordem numérica indicada.
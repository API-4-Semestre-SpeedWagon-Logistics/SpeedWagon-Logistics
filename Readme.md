#   SpeedWagon Logistics

Projeto baseado na metodologia ágil SCRUM, procurando desenvolver a Proatividade, Autonomia, Colaboração e Entrega de Resultados dos estudantes envolvidos

# Índice
* [Objetivo do Projeto](#objetivo-do-projeto)
* [Equipe](#Equipe)
* [Product Backlog](#Product-Backlog)
* [Tecnologias Utilizadas](#Tecnologias-Utilizadas)
* [Registro das Sprints](#Registro-das-Sprints)


# Projeto (API) 
Este projeto tem como objetivo o desenvolvimento de uma solução em Business Intelligence voltada para o controle, análise e acompanhamento da evolução e giro de estoque de materiais na CPTM. A proposta inclui a criação de dashboards interativos em Power BI que organizem e integrem as bases de dados do ERP ALVO — como os relatórios de cadastro de materiais, saldos físicos e movimentações históricas —, permitindo analisar indicadores de rotatividade, impacto financeiro e riscos operacionais, com foco na prevenção de falta de peças para a manutenção dos trens e na redução de capital parado.

# Equipe
|  Função        |  Nome               | Linkedln & GitHub |
|------------------|----------------------|------------------------------------------------------------------|
|  Scrum Master | Derick Fernandes Souta        |[![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/derick-souta-aa43813b1?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/DerickSouta) |  |
| Dev Team | Fabiano | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)]() [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Fabiano1301) |
|  Product Owner     | Jonathan Wesley Ferreira da Silva      |[![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/jonathan-wesley-ferreira-da-silva-55700a392/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/JonathanWesleyFS) |  |
| Dev Team | Julio Eduardo Bustamante Mancisidor | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)]() [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)]() |
| Dev Team | Lucas Daniel da Silva Faria | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-daniel-0349b83bb?utm_source=share_via&utm_content=profile&utm_medium=member_android) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/LucasDaniel7777)
|  Dev Team | Lucas Silva Daniel          |[![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-silva-0a5952382/?skipRedirect=true) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/LucasSilva59) |  |
| Dev Team | Tiago | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)]() [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)]() |


# Objetivo do Projeto
Este projeto tem como objetivo desenvolver uma ferramenta de Business Intelligence focada na gestão, controle e análise do estoque de materiais de manutenção da CPTM, visando:
* Integrar e organizar as diferentes bases de dados brutas obtidas do ERP ALVO, como cadastros de materiais, movimentações históricas, saldos e centros de custo;
* Analisar os indicadores de desempenho do estoque da CPTM, com foco na velocidade de rotatividade (giro), estoque médio e o valor total do capital imobilizado;
* Desenvolver um dashboard interativo no Power BI com visões gerenciais e operacionais, incluindo uma versão otimizada para visualização rápida em celulares e tablets;
* Implementar um sistema automático de classificação de importância e alertas visuais de risco para identificar materiais parados há muito tempo, em excesso ou com risco de falta para a manutenção das frotas de trens.
  


## Tecnologias Utilizadas

* Power BI
* Google Drive
* ScreenToGif
* Python (Colab)
* Canva
* Pacote Office
* Whatsapp
* Discord
* NotebookLM



# Product Backlog

| Rank | Prioridade | User Story                                                                                                                                              | Estimativa | Sprint |
|------|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|------------|--------|
|1|Alta|Como Gerente de Logística da CPTM, quero que os dados brutos das planilhas do ERP sejam limpos, organizados e conectados no Power BI, para que os relatórios não apresentem duplicidades ou informações erradas.|13|1|
|2|Alta|Como Gerente de Logística da CPTM, quero visualizar um protótipo visual no papel ou ferramenta de design, para avaliar o visual dos gráficos e a distribuição das informações antes do início da construção do dasboard.|3|1|
|3|Alta|Como Supervisor do Almoxarifado, quero pesquisar e filtrar informações por Almoxarifado, Período e Tipo de Material, para analisar apenas os dados do galpão pelo qual sou responsável.|3|1|
|4|Alta|Como Gerente de Logística da CPTM, quero que o protótipo de design aprovado seja construído no Power BI contendo os cartões de Quantidade Total, Valor Imobilizado e Estoque Médio, para ver o início operacional do painel com números reais.|8|2|
|5|Alta|Como Gerente de Logística da CPTM, quero gráficos que mostrem o histórico mensal de compras e consumos de materiais, para acompanhar o crescimento ou queda do capital investido ao longo do tempo.|5|2|
|6|Alta|Como Analista de Compras, quero visualizar o ranking de custos de materiais e a classificação automática da Curva ABC por consumo, para focar as negociações de novos contratos nos materiais críticos.|5|2|
|7|Média|Como Supervisor do Almoxarifado, quero acompanhar a velocidade de rotatividade (Giro) e o tempo médio que cada categoria de material fica guardada no galpão, para otimizar a ocupação do espaço físico.|3|2|
|8|Alta|Como Supervisor do Almoxarifado, quero avisos visuais automáticos (alertas) de estoque parado há mais de 180 dias, estoque com risco de ruptura (falta) ou sobra de itens, para tomar decisões rápidas nas oficinas.|5|3|
|9|Alta|Como Gerente de Logística da CPTM, quero acessar o painel em uma versão otimizada para celulares e tablets com navegação rápida de até 2 cliques, para acompanhar os indicadores durante vistorias. |13|3|
|10|Alta|Como Analista de Compras, quero ver o nível de cobertura de estoque (em meses) e um gráfico de previsão de consumo de materiais para os próximos 3 meses, para programar as compras futuras e evitar surpresas. |8|3|
|11|Média|Como Gerente de Logística da CPTM, quero receber um manual do usuário simples e uma lista explicativa dos dados do painel, para que meus colaboradores saibam usar e manter o dashboard funcionando de forma autônoma. |5|3|



  
# Registro das Sprints

| Sprint            | Previsão   | Status   | Histórico |
|-------------------|------------|----------|-----------|
| 00                | 02/09/2026 | Concluído  | [MVP](https://youtu.be/9Wz9cjv0Y-4?si=7GpXw8TLsedtJnFp)
| 01                | 30/09/2026 | Em andamento  | [MVP](https://github.com/API-4-Semestre-SpeedWagon-Logistics/SpeedWagon-Logistics/blob/main/MVP/sp1.md)  |
| 02                | 28/10/2026 | Planejando  | [MVP](https://github.com/API-4-Semestre-SpeedWagon-Logistics/SpeedWagon-Logistics/blob/main/MVP/sp2.md)  |
| 03                | 25/11/2026 | Planejando  | [MVP](https://github.com/API-4-Semestre-SpeedWagon-Logistics/SpeedWagon-Logistics/blob/main/MVP/sp3.md)  |
| Feira de Soluções | 03/12/2026 | Planejando  | [MVP](#)  |

# 📌 MVP - [Nome do Projeto]

## 🎯 Objetivo do MVP
> O objetivo é resolver a falta de visibilidade sobre os indicadores financeiros e de rotatividade do estoque da CPTM. Dessa forma, validamos a hipótese de que a implementação do layout no Power BI com dados reais e a sua disponibilização em uma versão web permitem monitorar efetivamente a evolução do capital investido e a criticidade dos materiais. O valor final é entregar aos gestores um dashboard funcional com indicadores de Valor Imobilizado, Curva ABC e Giro de Estoque, garantindo uma base interativa para direcionar negociações de contratos e otimizar o espaço físico dos galpões. 

---

## 📝 Descrição da Solução
> Nesta etapa, focaremos na implementação do layout aprovado no Power BI utilizando dados reais, bem como na disponibilização de uma versão do dashboard integrada em um site. A ferramenta incluirá, como funcionalidades principais, os indicadores de Quantidade Total, Valor Imobilizado e Estoque Médio, acompanhados por gráficos de histórico mensal, classificação automática da Curva ABC e o cálculo do giro de estoque. A principal limitação conhecida nesta fase é a ausência de alertas visuais automáticos para riscos de ruptura, excesso ou material parado, bem como a falta de otimização para dispositivos móveis. Por fim, o escopo foi reduzido para garantir apenas o funcionamento e a precisão dos cálculos financeiros e de rotatividade na versão web, validando o núcleo analítico da ferramenta antes de se avançar para os sistemas de alerta e previsão da última sprint.

---

## 👥 Personas / Usuários-Alvo
- **Persona 1:** Gerente de Logística da CPTM – Este perfil atua na gestão estratégica do abastecimento e controlo de materiais da empresa. A sua necessidade central envolve garantir que os dados brutos extraídos do ERP ALVO sejam devidamente limpos e estruturados, para assegurar que os futuros relatórios estejam livres de duplicidades e erros. As suas dores são atendidas nesta etapa através da apresentação de um protótipo de layout, permitindo-lhe aprovar a distribuição visual das informações de forma segura antes do desenvolvimento completo do dashboard.  
- **Persona 2:** Supervisor do Almoxarifado – Este perfil atua na gestão operacional diária e na organização física dos armazéns (galpões). A sua necessidade central é conseguir segmentar a base de dados, filtrando as informações especificamente por Almoxarifado, Período e Tipo de Material. As suas dores relativas ao excesso de informação desorganizada são resolvidas ao receber uma funcionalidade que lhe permite focar a análise exclusivamente nos dados referentes ao seu próprio galpão, facilitando o acompanhamento e a operação local.
- **Persona 3:** Analista de Compras – Este perfil atua no planejamento de aquisições e na negociação de novos contratos de materiais para a manutenção da frota. A sua necessidade central envolve ter visibilidade clara sobre o ranking de custos, a classificação da Curva ABC e a previsão de cobertura de estoque para os próximos meses. As suas dores ligadas à imprevisibilidade de demandas e compras urgentes são atendidas na medida em que a limpeza e estruturação dos dados do ERP neste MVP criarão a base confiável para que, nas próximas entregas, ele consiga planejar compras futuras com segurança e focar os esforços de negociação exclusivamente nos materiais mais críticos.

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| US1 | Como Gerente de Logística da CPTM, quero que o layout aprovado seja implementado no Power BI com indicadores de Quantidade Total, Valor Imobilizado e Estoque Médio, para validar a operação do painel com dados reais.        | Alta       | 5   |
| US2 | Como Gerente de Logística da CPTM, quero gráficos do histórico mensal de compras e consumo, para monitorar a evolução do capital investido ao longo do tempo.         | Alta    | 5   |
| US3|Como Analista de Compras, quero visualizar o ranking de custos e a classificação automática da Curva ABC por consumo, para direcionar as negociações de novos contratos aos materiais mais críticos.| Alta|8|
|US4| Como Gerente de Logística da CPTM, quero que o dashboard tenha uma versão em um site, para ampliar minhas possibilidades de soluções.| Alta| 13|
|US5|Como Supervisor do Almoxarifado, quero acompanhar o giro de estoque e o tempo médio de permanência dos materiais, para otimizar o uso do espaço físico do galpão.|Média|8|

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | quero que os dados brutos do ERP sejam limpos e estruturados   | Concluído|
| 02     |quero que o layout aprovado seja implementado no Power BI com indicadores de Quantidade Total, Valor Imobilizado e Estoque Médio | Em andamento |
|02|quero gráficos do histórico mensal de compras e consumo |Em andamento|
|02|quero visualizar o ranking de custos e a classificação automática da Curva ABC por consumo |Em andamento|
|02|quero que o dashboard tenha uma versão em um site |Em andamento|
|02|quero acompanhar o giro de estoque e o tempo médio de permanência dos materiais| Em andamento|
|03|quero receber alertas visuais sobre estoque parado há mais de 180 dias, risco de ruptura ou excesso|Em andamento|

---

## 📊 Critérios de Aceitação
- O MVP deve permitir que o usuário visualize e interaja com o dashboard implementado no Power BI (e na sua versão em site), analisando com dados reais os indicadores de Quantidade Total, Valor Imobilizado e Estoque Médio. 
- O sistema deve registrar o cálculo correto e a exibição gráfica do histórico mensal de compras e consumo, além da classificação automática da Curva ABC e do tempo médio de permanência. 
- Métricas coletadas: Quantidade Total, Valor Imobilizado, Estoque Médio, classificação da Curva ABC por consumo, giro de estoque e tempo médio de permanência dos materiais.

---

## 📈 Métricas de Validação
- Número de utilizadores que testaram o MVP (Validação com Stakeholders): Número de apresentações e rodadas de homologação realizadas com o cliente (CPTM) e orientadores para validar a precisão dos indicadores reais (Quantidade Total, Valor Imobilizado, Estoque Médio e Curva ABC) implementados no Power BI e na sua nova versão em site.
- Feedback qualitativo (Avaliação de Usabilidade e Clareza): Coleta de perceções (positivas/negativas) dos utilizadores finais (como o Gerente de Logística e o Supervisor do Almoxarifado) sobre a facilidade de navegação no dashboard e a clareza na interpretação dos gráficos de histórico mensal de compras/consumo e do giro de stock.  
- Indicadores de negócio (Aderência aos Objetivos de Negócio): Capacidade técnica do MVP em calcular corretamente o giro de stock, o tempo médio de permanência e o valor total do capital imobilizado, comprovando que a ferramenta entrega a base analítica necessária para futuras ações de redução de custos e otimização do espaço físico dos galpões.

---

## 🚀 Próximos Passos
- Melhorias planejadas após feedback  
- Ajustes de usabilidade  
- Expansão de funcionalidades para próximo incremento  

---

## 📂 Anexos / Evidências
## Dashboard:
![Dashboard](https://github.com/API-4-Semestre-SpeedWagon-Logistics/SpeedWagon-Logistics/blob/main/Imagens/PowerBIV.2%20imagem%201.png)
![Dashboard](https://github.com/API-4-Semestre-SpeedWagon-Logistics/SpeedWagon-Logistics/blob/main/Imagens/PowerBIV.2%20imagem%202.png)

Link para Dashboard: https://app.powerbi.com/view?r=eyJrIjoiNjRkN2Y3ZDYtNjhkOS00OGY3LWI5NTItMTQyY2I0OTgwMTg4IiwidCI6ImVhYmU2NGM1LTY4ZjUtNGE3Ni04MzAxLTk1NzdhNjc5ZTQ0OSIsImMiOjR9

---

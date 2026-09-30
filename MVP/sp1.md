# 📌 MVP - SpeedWagon Logistics

## 🎯 Objetivo do MVP
> O objetivo é resolver a desestruturação dos dados brutos do ERP ALVO. Dessa forma, validamos que bases limpas e um protótipo visual aprovado garantem a construção de um dashboard confiável. O valor entregue é a visualização antecipada do layout com filtros de Almoxarifado, Período e Tipo de Material, permitindo análises focadas e seguras.  


---

## 📝 Descrição da Solução
> Nesta etapa, focaremos na limpeza e estruturação dos dados brutos extraídos do ERP ALVO, bem como na construção e aprovação de um protótipo visual do dashboard. A ferramenta incluirá, como funcionalidades principais, filtros interativos por Almoxarifado, Período e Tipo de Material. A principal limitação conhecida é a dependência da qualidade dos dados originais do ERP, que podem exigir tratamentos complexos para eliminar duplicidades. Por fim, o escopo foi reduzido para entregar apenas a validação da estrutura de dados e do layout visual, garantindo que as informações possam ser segmentadas corretamente antes da implementação dos indicadores financeiros nas próximas sprints.  
 

---

## 👥 Personas / Usuários-Alvo
- **Persona 1:** Gerente de Logística da CPTM – Este perfil atua na gestão estratégica do abastecimento e controlo de materiais da empresa. A sua necessidade central envolve garantir que os dados brutos extraídos do ERP ALVO sejam devidamente limpos e estruturados, para assegurar que os futuros relatórios estejam livres de duplicidades e erros. As suas dores são atendidas nesta etapa através da apresentação de um protótipo de layout, permitindo-lhe aprovar a distribuição visual das informações de forma segura antes do desenvolvimento completo do dashboard.  
- **Persona 2:** Supervisor do Almoxarifado – Este perfil atua na gestão operacional diária e na organização física dos armazéns (galpões). A sua necessidade central é conseguir segmentar a base de dados, filtrando as informações especificamente por Almoxarifado, Período e Tipo de Material. As suas dores relativas ao excesso de informação desorganizada são resolvidas ao receber uma funcionalidade que lhe permite focar a análise exclusivamente nos dados referentes ao seu próprio galpão, facilitando o acompanhamento e a operação local.  

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| US1 | Como Gerente de Logística da CPTM, quero que os dados brutos do ERP sejam limpos e estruturados, para garantir relatórios livres de duplicidades e erros.         | Alta       | 13   |
| US2 | Como Gerente de Logística da CPTM, quero visualizar um protótipo do layout, para aprovar a distribuição visual das informações antes do desenvolvimento do dashboard.         | Alta      | 3   |
| US3 | Como Supervisor do Almoxarifado, quero filtrar as informações por Almoxarifado, Período e Tipo de Material, para focar a análise exclusivamente nos dados do meu galpão.         | Alta      | 3   |

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | quero que os dados brutos do ERP sejam limpos e estruturados                      | Concluído|
| 01     | quero visualizar um protótipo do layout                           | Concluído |
| 01     | quero filtrar as informações por Almoxarifado, Período e Tipo de Material                          | Concluído |
| 02     | quero que o layout aprovado seja implementado no Power BI com indicadores de Quantidade Total, Valor Imobilizado e Estoque Médio                          | Planejando |
| 03     | quero receber um manual do usuário e um dicionário explicativo dos dados                          | Planejando |


---

## 📊 Critérios de Aceitação
- O MVP deve permitir que o usuário aplique filtros no protótipo do dashboard por Almoxarifado, Período e Tipo de Material, para focar a análise exclusivamente nos dados do seu interesse.  
- O sistema deve registrar a limpeza e estruturação corretas dos dados brutos extraídos do ERP ALVO, garantindo relatórios livres de duplicidades e erros e validando o protótipo de layout. 
- Métricas coletadas: Validação estrutural da base de dados (integridade) e aprovação visual da distribuição das informações no protótipo do dashboard.  

---

## 📈 Métricas de Validação
- Validação com Stakeholders: Número de apresentações e rodadas de homologação realizadas com o cliente (CPTM) ou orientadores para aprovar o protótipo do layout visual e validar a estruturação dos dados extraídos do ERP ALVO.
- Avaliação de Usabilidade e Clareza: Coleta de perceções (feedback qualitativo) sobre a facilidade de navegação pelo protótipo e a clareza na aplicação dos filtros de Almoxarifado, Período e Tipo de Material.  
- Aderência aos Objetivos de Negócio: Capacidade técnica do MVP em garantir a entrega de relatórios e bases de dados limpas, livres de duplicidades e erros, fornecendo uma fundação sólida e confiável para o futuro desenvolvimento dos indicadores gerenciais. 

---

## 🚀 Próximos Passos
- Melhorias planejadas após feedback  
- Ajustes de usabilidade  
- Expansão de funcionalidades para próximo incremento  

---

## 📂 Anexos / Evidências
💡 *Clique na imagem abaixo para abrir o relatório completo em PDF.*
[![Prévia do Relatório](https://github.com/API-4-Semestre-SpeedWagon-Logistics/SpeedWagon-Logistics/blob/main/Imagens/Capa%20do%20relat%C3%B3rio%20do%20MVP%201.png)](https://github.com/API-4-Semestre-SpeedWagon-Logistics/SpeedWagon-Logistics/blob/main/Docs/Relat%C3%B3rio%20API%20-%20SpeedWagon%20Logistics%20-%20MVP%201.pdf)
## Protótipo exemplar não funcional de um Dashboard.
![Protótipo do Dashboard](https://github.com/API-4-Semestre-SpeedWagon-Logistics/SpeedWagon-Logistics/blob/main/Imagens/Prot%C3%B3tipo%20PowerBI%20Imagem.jpeg)
## Protótipo de um site interativo visualizando os dados.  
![Dashboard Inícial](https://github.com/API-4-Semestre-SpeedWagon-Logistics/SpeedWagon-Logistics/blob/main/Imagens/PowerBI%20imagem.png)
## Analise e filtragem dos arquivos da CPTM
![Demonstração do Script Python 1](https://github.com/API-4-Semestre-SpeedWagon-Logistics/SpeedWagon-Logistics/blob/main/GIFS/ARQUIVO%201%20FINAL.gif)
-link
![Demonstração do Script Python 2,3,4](https://github.com/API-4-Semestre-SpeedWagon-Logistics/SpeedWagon-Logistics/blob/main/GIFS/ARQUIVO%202%2C%203%2C%204%20FINAL.gif)
![Demonstração do Script Python 5](https://github.com/API-4-Semestre-SpeedWagon-Logistics/SpeedWagon-Logistics/blob/main/GIFS/ARQUIVO%205%20FINAL.gif)
![Demonstração do Script Python 6](https://github.com/API-4-Semestre-SpeedWagon-Logistics/SpeedWagon-Logistics/blob/main/GIFS/ARQUIVO%206%20FINAL.gif)
![Demonstração do Script Python 7](https://github.com/API-4-Semestre-SpeedWagon-Logistics/SpeedWagon-Logistics/blob/main/GIFS/ARQUIVO%207%20FINAL.gif)
![Demonstração do Script Python 8](https://github.com/API-4-Semestre-SpeedWagon-Logistics/SpeedWagon-Logistics/blob/main/GIFS/ARQUIVO%208%20FINAL.gif)
![Demonstração do Script Python 9](https://github.com/API-4-Semestre-SpeedWagon-Logistics/SpeedWagon-Logistics/blob/main/GIFS/ARQUIVO%209%20FINAL.gif)
![Demonstração do Script Python 10](https://github.com/API-4-Semestre-SpeedWagon-Logistics/SpeedWagon-Logistics/blob/main/GIFS/ARQUIVO%2010%20FINAL.gif)

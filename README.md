# Projeto - Leishmaniose no Brasilo
# Project - Leishmaniose in Brazil

Integrantes do grupo

Nome                     | RA    | Especialização
-------------------------| ------| --------------
Carolina Muller Ferreira |210904 | Saúde
Letícia Moreno           |235497 | Saúde
Lucas Feliciano da Silva |182487 | TI 
Paulo Victor             |224943 | TI

## Vídeo

https://user-images.githubusercontent.com/81878392/114087766-a79e2480-988a-11eb-9bcd-a57aa99f95a1.mp4

## Descrição Resumida do Projeto

   Em 1982, a síndrome da imunodeficiêcia adquirida (AIDS) foi reconhecida como doença infecciosa pelo Center for Disease, Control and Prevention (CDC) , cujo contágio era feito por meio do contato com fluidos corporais. (1) Estima-se que a prevalência global de pessoas com HIV aumentou de 1990 (8.74 milhões de pessoas) a 2017 (36.8 milhões de pessoas). (2) Em contraponto, as mortes globais por HIV que atingiram o pico em 2006, estão reduzindo ao longo das décadas.(2) Portanto, apesar de haver mais pessoas infectadas com a doença, fatores como: o tratamento, prevenção, técnicas de detecção prévia e até aumento da qualidade de vida, tem permitido uma menor mortalidade, ou seja, maior expectativa de vida de pacientes com HIV.
   
   De acordo com o Boletim epidemiológico HIV/Aids de 2020, de 2007 até junho de 2020, foram notificados no Sistema de Informações de Agravos de Notificação, 342.459 casos de infecção pelo HIV no Brasil, com maior prevalência em homens (69,4%), na região Sudeste (44,4%) e entre 20 e 34 anos (52,7%). Já no ano anterior, foram notificados 41.919 casos de infecção pelo HIV, mostrando aumento de casos em um ano de notificação e confirmando a expectativa global de casos. (3)
   
   Uma das fontes de dados sobre a saúde dos brasileiros são as pesquisas nacionais realizadas pelo Instituto Brasileiro de Geografia e estatística nos domicílios brasileiros. As últimas pesquisas nacionais realizadas foram: a Pesquisa Nacional de Demografia e Saúde, com última edição em 2006, a Pesquisa de orçamentos familiares, com última edição em 2008 e a Pesquisa Nacional por Amostra de Domicílios, com última edição em 2015, não tiveram edições e atualizações recentes sobre o HIV. A Pesquisa Nacional de Saúde realizada em 2019 trouxe temas como alimentação, tabagismo e doenças crônicas, mas não trouxeram dados exclusivos de HIV.(4) Outra fonte de dados da população brasileira é são os censos nacionais e a Vigilância de Doenças Crônicas por Inquérito Telefônico – VIGITEL, dos quais os censos tiveram as últimas edições em 2000 e 2010 e o Vigitel com útlima versão publicada em 2019, ambos não contém dados atualizados sobre o tema. (4) 
   
   Na ausência de estimativas nacionais, a síntese dos estudos individuais é uma alternativa para estimar e monitorar doenças como a AIDS. As revisões sistemáticas disponíveis não apresentam de forma eficaz os bancos de dados de suas pesquisas disponíveis para avaliação. A Ciência Aberta é um movimento recente que incentiva a transparência da pesquisa científica desde a concepção da investigação até o uso de softwares abertos, como repositórios Figshare ou Dryad, com o objetivo de coloaboração na pesquisa, atualização de dados do tema e transparência da pesquisa. Mas, como muitos pesquisadores são bastante conservadores em muitas de suas práticas, muitos dados ainda não são tratados como abertos, dificultando reanálises ou novas abordagens como a que esse trabalho se destina. (5)
   
   Portanto o objetivo desse projeto é avaliar a disponibilidade de banco de dados sobre o HIV, avalia-los estatisticamente buscando a prevalência nas últimas décadas e a predição para os próximos anos, bem como categorizar os resultados encontrados e avaliar perante mortalidade nesse período.
      
## Perguntas da Pesquisa 
 
Letra/significado            | Correlação    
-----------------------------| ------
P (pessoa/pessoas)           | brasileiros adultos
I (intervenção)              | não temos
C (comparativo ou comparador)| não temos
O (desfecho a se avaliar)    | HIV/AIDS
S (tipo de estudo)           | prevalência de adultos brasileiro com HIV nas últimas décadas e predição para o futuro. E categorização por sexo e idade.

Perguntas para nosso projeto:
Qual a prevalência de adultos com HIV no Brasil nas últimas décadas? E por idade, sexo, região?
Qual a predição da prevalência de adultos com HIV no Brasil para as próximas décadas?

Hipóteses: Confirmar a maior prevalência de HIV no Brasil no últimos anos, verificando os subgrupos idade, sexo e regiões brasileiras.
           
## Bases de dados

Nome do banco                |Inclusão ou Exclusão?| Motivo                                                   
-----------------------------| --------------------|----------------------------------------------------------------------------------------------------------------------       
Indicadores HIV              |Inclusão             |Contém todos os dados do Brasil por ano, região e sexo
Estimativas da População     |Inclusão             |Contém dados da população em geral por ano para calculo de prevalência
População - censo de 2010    |Inclusão             |Contém dados da população em 2010 para calculo de prevalência
Planilhas HIV                |Possível Inclusão    |Contém várias planilhas de dados, mas nosso foco será os testes rápidos de HIV em 2020, 2019, 2018 e 2017-2011
Painel de Mortalidade CID-10 |Possível Inclusão    |Dados de óbito contém na planilha de Indicadores de HIV já incluida mas pode servir de referência ou base
DATASUS - Mortalidade        |Possível Inclusão    |Dados de óbito contém na planilha de Indicadores de HIV já incluida mas pode servir de referência ou base
TABNET                       |Exclusão             |Dados estão menores o que sugere que contém apenas alguns dados de notificação - dados supeitos de confiança    
Indicadores HIV              |Exclusão             |Com dados somente de Monitoramento Clínico de HIV e não casos gerais
Indicadores HIV              |Exclusão             |Gestantes Vivendo com HIV, com foco nas gestantes e não na população toda. Contém um PowerBI, não é um banco de dados
Indicadores HIV              |Exclusão             |Gestantes Vivendo com HIV, com foco nas gestantes  e não na população toda.
Indicadores HIV              |Exclusão             |Painel de monitoramento de dados de HIV durante a pandemia da COVID-19. Avaliação com co-patologia, e não só HIV. Sem banco.
Indicadores HIV              |Exclusão             |Painel das Maternidades 2020 , com foco nas gestantes  e não na população toda. Dados em PowerBi e ausência de banco de dados
DATASUS                      |Exclusão             |Não é possível extrair sem o app TABWIN porém não foi possível baixar o app e consequentemente avaliar os dados
DATASUS                      |Exclusão             |MORBIDADE HOSPITALAR DO SUS - foco somente hospitalar e não como um todo
Latin American Country HIV   |Exclusão             |Baseado em dados de predição. Contém arquivos que cita de onde vem os dados brutos, mas esses são de dificil extração.
COAP                         |Exclusão             |Dados do Contrato Organizativo da Ação Pública da Saúde - COAP e não essencialmente utilizáveis para avaliar a população
UNAIDS                       |Exclusão             |São relatórios e não banco de dados
IBGE SIDRA                   |Exclusão             |Contém a Taxa de incidência de AIDS e não os dados brutos e é limitada pois contém somente os anos de 2000-2012
Estatísticas do TABNET       |Exclusão             |Contém estatisticas de mortalidade, internações, demografia, etc, mas não dados específicos de HIV. Dados de 2013 a 2018.
Séries estatísticas IBGE     |Exclusão             |Contém a Taxa de incidência de AIDS e não os dados brutos e é limitada pois contém somente os anos de 1980-2008
Inquéritos nacionais         |Exclusão             |Pesquisas nacionais - Não tiveram edições e atualizações recentes sobre o HIV
Global Burden Disease        |Exclusão             |Paises fornecem os dados e o estudo faz estimativas, predições gerais - pode entrar como comparativo na discussão

Mais detalhes dos bancos e seus links: https://drive.google.com/drive/folders/1cvk76rLpl_bsDrseeYtbm6NNWk_a9-Bk?usp=sharing

## Metodologia

A metodologia que será utilizada para extrair conhecimento dos bancos de dados escolhidos é a CRISP-DM. Esta técnica de processamento de dados consiste em 6 fases: Entendimento do Negócio, Entendimento dos Dados, Processamento dos Dados, Modelamento, Avaliação e Entrega/Distribuição do Projeto. Essas etapas são iterativas, cíclicas e podem ser mais detalhadas à medida que o projeto avança, contendo tarefas que partem do âmbito geral até o mais específico, evoluindo no decorrer do projeto.  

Seguindo o modelo de referência do CRISP-DM 1.0, e analisando o andamento do projeto podemos dizer que a etapa atual do projeto está entre a etapa de Entendimento do Negócio e a etapa de Entendimento dos Dados uma vez que as perguntas do projeto já foram feitas e o banco de dados principal já foi escolhido, atualmente estão sendo feitos os processos de descrição e exploração dos dados.  Vale notar que, devido a característica cíclica do CRISP-DM, essas etapas e processos não são fixos podendo ser reformulados caso seja necessário, outra observação importante é que algumas das tarefas gerais de algumas etapas não se aplicam, como por exemplo a tarefa Manutenção e plano de manutenção na etapa de Distribuição.

<img src="assets/images/CRISPDM.png" alt="CRISP-DM e suas etapas" width="400" heigth="400"/>

**Imagem 1:** - CRISP-DM e suas etapas

![image](assets/images/CRISPDM_detalhado.png "CRISP-DM e suas etapas detalhadas")

**Imagem 2:** - CRISP-DM e suas etapas detalhadas, em negrito as tarefas gerais e em itálico seus respectivos resultados.


## Ferramentas

Software Phyton/Orange - Categorização dos dados, análise estatísticas, variabilidade dos dados, classificação e análise da distribuição/correlação  
Software STATA 14.2 - análise de prevalência

## Cronograma

Etapa (s)                                  | Data (s)
------------------------------------------ | ------
Entrega do Plano do Projeto - E1           | 13/abril
Trabalhar com os bancos excel              | 19 a 23/abril
Avaliações estatisticas                    | 26 a 30/abril
Primeiros resultados                       | 3 a 7/maio
Entrega da bases de dados de trabalho - E2 | 11/maio
Correções de erros e resultados            | 17 a 21/maio
Comparação com a literatura                | 24 a 28/maio
Embasamento teorico do trabalho final      | 31 a 04/junho
Montar a apresentação                      | 7 a 11/junho
Treinamento da apresentação                | 14 a 18/junho
Entrega Final e apresentações              | 24/junho

## Referências
1. Greene WC. A history of AIDS: looking back to see ahead. Eur J Immunol. 2007 Nov;37 Suppl 1:S94-102. doi: 10.1002/eji.200737441. Erratum in: Eur J Immunol. 2008 Jan;38(1):309. PMID: 17972351.
2. Frank, Tahvi D., et al. "Global, regional, and national incidence, prevalence, and mortality of HIV, 1980–2017, and forecasts to 2030, for 195 countries and territories: a systematic analysis for the Global Burden of Diseases, Injuries, and Risk Factors Study 2017." The lancet HIV 6.12 (2019): e831-e859.
3. Site, Doenças de Condições Crônicas e Infecções sexualmente trasnmissíveis. "Disponível em: http://www.aids.gov.br/pt-br/pub/2020/boletim-epidemiologico-hivaids-2020" Acesso em April, 05 (2021).
4. Site, I.B.G.E. "Disponível em: https://www.ibge.gov.br/estatisticas/sociais/saude.html" Acesso em April, 05 (2021).
5. SILVA, Fabiano Couto Corrêa da  and  SILVEIRA, Lúcia da. O ecossistema da Ciência Aberta. Transinformação [online]. 2019, vol.31 [cited  2021-04-05], e190001. Available from: <http://www.scielo.br/scielo.php?script=sci_arttext&pid=S0103-37862019000100302&lng=en&nrm=iso>.  Epub Sep 23, 2019. ISSN 2318-0889.  https://doi.org/10.1590/2318-0889201931e190001.
6. CRISP-DM 1.0: Step-by-step mining guide, The CRISP-DM consortium, Agosto, 2000.

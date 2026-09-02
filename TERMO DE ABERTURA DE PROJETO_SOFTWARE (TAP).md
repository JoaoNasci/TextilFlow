# TERMO DE ABERTURA DE PROJETO/SOFTWARE (TAP)

## TêxtilFlow — Sistema Integrado de Planejamento e Controle da Produção para Tecelagem

**Versão:** 1.0 — Documento-base para avaliação  
**Organização:** [Nome da empresa]  
**Público-alvo:** Pequenas e médias empresas do setor de tecelagem  
**Unidade/área:** [Unidade industrial / Diretoria responsável]  
**Elaborado por:** [Nome do responsável]  
**Data de emissão:** [Preencher após aprovação]  

> **Nota de preenchimento.** Os campos entre colchetes são informações institucionais que devem ser ajustadas pela empresa. Os valores de investimento e prazo são estimativas preliminares para apoiar a decisão de iniciar o projeto.

---

O TêxtilFlow deverá manter arquitetura modular e possibilidade de integração futura com outros sistemas corporativos, sem ampliar o escopo inicial para além das necessidades da tecelagem.

---

## 1. Identificação e autorização do projeto

| Campo | Definição preliminar |
|---|---|
| **Nome do projeto/software** | TêxtilFlow — Sistema Integrado de Planejamento e Controle da Produção para Tecelagem |
| **Natureza** | Desenvolvimento ou implantação de software de Planejamento e Controle da Produção (PCP), com especialização para operações de tecelagem. |
| **Unidade patrocinadora** | [Diretoria Industrial / Diretoria Executiva] |
| **Gerente do projeto** | [Nome e cargo] |
| **Área proprietária do produto** | PCP, em conjunto com Produção, Engenharia de Processos e TI. |
| **Abrangência inicial** | [Fábrica/unidade], contemplando programação, execução, apontamento, qualidade, manutenção e indicadores da tecelagem. |
| **Critério de autorização** | Aprovação deste TAP pelo patrocinador e liberação do orçamento inicial. |

### 1.1. Patrocinador (sponsor)

O patrocinador proposto é a **Diretoria Executiva ou Diretoria Industrial da [Nome da empresa]**, representada por **[nome, cargo e contato]**. Cabe ao patrocinador assegurar o apoio financeiro e institucional, priorizar o projeto perante as demais iniciativas, remover impedimentos que dependam da alta gestão, aprovar mudanças relevantes de escopo, prazo ou orçamento e validar a entrega final.

O patrocinador deverá indicar um responsável com autoridade suficiente para tomar decisões sobre prioridades industriais, disponibilização de usuários-chave e integração entre as áreas de PCP, tecelagem, qualidade, manutenção, estoque, compras, expedição e tecnologia da informação.

---

## 2. Justificativa do software

A operação de tecelagem envolve a coordenação de artigos, fichas técnicas, fios, lotes, receitas, teares, velocidades, setups, equipes, turnos, inspeções, perdas, paradas e reprocessamentos. Quando essas informações permanecem distribuídas entre planilhas, registros manuais, sistemas que não conversam entre si e controles paralelos, a empresa tende a ter dificuldade para formar uma visão única e atualizada da capacidade produtiva e do andamento das ordens.

A situação atual a ser investigada e tratada pelo projeto é caracterizada, preliminarmente, por **baixa integração entre planejamento e execução**, atualizações manuais, pouca rastreabilidade do fio ao tecido, dificuldade para identificar gargalos, mudanças de programação com comunicação tardia, apontamentos incompletos e indicadores calculados após o fato. Esses problemas podem gerar atrasos, excesso de estoque em processo, paradas não analisadas, perdas de matéria-prima, retrabalho, baixa confiabilidade dos prazos e dependência de conhecimento individual.

O software é necessário para consolidar dados operacionais, apoiar a programação realista dos teares, registrar o que efetivamente ocorreu no chão de fábrica e transformar os dados em informação para decisão. A solução também deverá criar uma base para melhoria contínua, auditoria de processos, rastreabilidade e futura integração com um ERP ou sistema corporativo.

---

## 3. Objetivo geral

Desenvolver ou implantar um sistema de PCP especializado em tecelagem para **planejar, programar, acompanhar e controlar a produção**, integrando informações de pedidos, artigos, fios, teares, ordens de produção, qualidade, manutenção e estoque, de modo a aumentar a previsibilidade dos prazos, a rastreabilidade e a eficiência operacional.

---

## 4. Objetivos específicos e metas parciais

| Objetivo específico | Meta parcial proposta | Indicador de acompanhamento |
|---|---|---|
| Estruturar o cadastro industrial | Padronizar artigos, fios, receitas, teares, operações, turnos, calendários e motivos de parada antes do piloto. | Percentual de cadastros críticos validados. |
| Planejar a capacidade | Disponibilizar visão de carga por tear, artigo, turno e período, considerando restrições conhecidas. | Percentual de ordens planejadas com capacidade verificada. |
| Programar a produção | Emitir sequência de produção e ordens de produção com prioridades, prazos e recursos definidos. | Aderência da programação ao plano aprovado. |
| Registrar a execução | Permitir apontamento de produção, perdas, paradas, trocas, observações e consumo de materiais. | Percentual de ordens apontadas no turno ou no dia. |
| Aumentar a rastreabilidade | Relacionar pedido, ordem, artigo, lote de fio, tear, turno, operador e lote de tecido. | Percentual de lotes rastreáveis de ponta a ponta. |
| Integrar qualidade e manutenção | Registrar inspeções e ocorrências de qualidade; relacionar paradas e chamados de manutenção à ordem ou ao tear. | Percentual de ocorrências com causa, responsável e tratamento registrados. |
| Disponibilizar indicadores | Criar painéis de produção, eficiência, paradas, perdas, qualidade, prazo e utilização de teares. | Atualização dos painéis conforme periodicidade definida. |
| Preparar expansão | Documentar integrações e modelo de dados para futuras integrações corporativas, sem ampliar o escopo inicial. | Documento de arquitetura e backlog de evolução aprovados. |

As metas percentuais definitivas deverão ser ajustadas após o diagnóstico da situação atual, a medição da linha de base e a validação com o patrocinador e os usuários-chave.

---

## 5. Benefícios esperados

Os benefícios abaixo são estimativas de referência e deverão ser confirmados por um diagnóstico inicial. O acompanhamento deverá comparar a linha de base do período anterior ao projeto com os resultados após o piloto e a estabilização.

| Horizonte | Benefício esperado | Forma de mensuração |
|---|---|---|
| Curto prazo — piloto e estabilização | Redução de controles paralelos e do tempo gasto na consolidação manual de informações. | Horas semanais dedicadas a planilhas e consolidações antes e depois do piloto. |
| Curto prazo — até 3 meses após a entrada em produção | Maior visibilidade das ordens, prioridades, paradas e carga dos teares. | Percentual de ordens com status atualizado e painel disponível para as áreas. |
| Médio prazo — até 6 meses | Melhoria da aderência da programação e redução de reprogramações evitáveis. | Aderência ao plano, quantidade de reprogramações e cumprimento de prazos. |
| Médio prazo — até 6 meses | Redução de perdas, esperas e horas improdutivas por causas não tratadas. | Quilogramas de perdas, horas de parada e causas recorrentes por tear. |
| Médio prazo — 6 a 12 meses | Aumento da rastreabilidade e da velocidade de investigação de desvios de qualidade. | Tempo para localizar lote, ordem, fio, tear e turno associados a uma ocorrência. |
| Longo prazo — após maturação | Base para integração com ERP, manutenção, estoque e outros sistemas corporativos. | Número de integrações implantadas e processos que utilizam dados únicos. |

Entre os **benefícios intangíveis**, destacam-se maior confiança nas informações, redução da dependência de conhecimento não documentado, fortalecimento da colaboração entre escritório e fábrica, responsabilização clara pelos apontamentos, cultura de gestão à vista, maior capacidade de aprendizado organizacional e melhor percepção do cliente sobre previsibilidade e qualidade.

---

## 6. Descrição breve do software e funcionalidades

O TêxtilFlow será uma aplicação web, com perfis de acesso por função, destinada a conectar o planejamento do PCP à execução da tecelagem. O sistema deverá permitir que a empresa mantenha uma fonte única de informações operacionais, sem impedir a integração com sistemas corporativos existentes.

### 6.1. Arquitetura tecnológica proposta

A solução será organizada em camadas, separando a interface dos usuários, as regras de negócio e o armazenamento persistente. A arquitetura prevista para o MVP é composta por React no front-end, Java com Spring Boot no back-end e PostgreSQL como banco de dados relacional.

| Camada | Tecnologia | Responsabilidade |
|---|---|---|
| **Front-end** | **React** | Interfaces web responsivas para PCP, supervisores, operadores de tear, qualidade, manutenção, estoque e gestão; formulários, consultas, dashboards e apontamentos. |
| **Back-end** | **Java + Spring Boot** | APIs, regras de negócio, autenticação, autorização, validações, integrações, processamento das ordens e serviços do sistema. |
| **Banco de dados** | **PostgreSQL** | Armazenamento de pedidos, artigos, fios, teares, receitas, ordens, lotes, apontamentos, qualidade, manutenção, estoques e indicadores. |

Fluxo lógico da solução: **usuários do PCP e do chão de fábrica → React → APIs e regras de negócio em Java/Spring Boot → PostgreSQL**.

| Módulo ou funcionalidade | Descrição preliminar |
|---|---|
| Cadastros mestres | Artigos, estruturas e receitas, fios, fornecedores, lotes, teares, características técnicas, calendários, turnos, equipes, operações e motivos de parada. |
| Carteira e demanda | Registro ou importação de pedidos, prioridades, datas prometidas, clientes, artigos e quantidades. |
| Planejamento de materiais | Verificação de disponibilidade e necessidade de fios, insumos e materiais de apoio. |
| Planejamento de capacidade | Visualização de carga, disponibilidade, restrições, setups e compatibilidade entre artigo e tear. |
| Programação e sequenciamento | Geração, ajuste e publicação de sequência de produção por tear, turno, artigo e prioridade. |
| Ordens de produção | Criação, liberação, suspensão, reprogramação, encerramento e consulta do histórico das ordens. |
| Apontamento de chão de fábrica | Registro de produção, refugos, perdas, paradas, trocas, início e fim de atividade, operador e turno. |
| Rastreabilidade | Consulta da relação entre pedido, ordem, artigo, lote de fio, tear, turno, operador e lote produzido. |
| Qualidade | Inspeções, defeitos, não conformidades, bloqueios, liberações, retrabalho e vínculo com o lote. |
| Manutenção | Registro de parada, chamado, causa, equipamento, intervenção e retorno à operação; integração futura com CMMS/ERP. |
| Estoque e movimentações | Consulta e registro das movimentações necessárias ao processo, com integração futura ao estoque corporativo. |
| Indicadores e painéis | Produção planejada versus realizada, eficiência, disponibilidade, paradas, perdas, qualidade, prazos e utilização dos teares. |
| Administração e auditoria | Usuários, perfis, permissões, logs, histórico de alterações, parâmetros e exportação de dados. |

**Fora do escopo inicial:** folha de pagamento, contabilidade, faturamento, CRM, compras completas, manutenção avançada, comércio eletrônico e módulos corporativos não essenciais ao PCP. Esses temas poderão compor integrações ou fases futuras, mediante aprovação formal.

---

## 7. Interessados no projeto (stakeholders)

| Stakeholder | Interesse ou responsabilidade | Participação esperada |
|---|---|---|
| Patrocinador e diretoria | Retorno do investimento, competitividade, governança e priorização. | Aprovar decisões, recursos, mudanças e resultados. |
| Gerência industrial | Eficiência, capacidade, cumprimento de prazos e integração entre áreas. | Validar escopo, metas, indicadores e implantação. |
| PCP | Planejamento, sequenciamento, prioridades e aderência ao plano. | Ser proprietário do processo e usuário-chave. |
| Supervisores e líderes de tecelagem | Execução, troca de turnos, paradas e gestão diária. | Validar telas e participar do piloto. |
| Operadores de teares | Apontamento simples, rápido e confiável no chão de fábrica. | Testar e utilizar as rotinas de execução. |
| Engenharia de processos | Fichas técnicas, parâmetros, métodos e tempos. | Validar dados técnicos e regras de produção. |
| Qualidade | Inspeção, defeitos, bloqueios, liberação e rastreabilidade. | Definir controles e critérios de aceite. |
| Manutenção | Paradas, causas, chamados, disponibilidade e intervenção. | Definir eventos e integração com ativos. |
| Almoxarifado/estoque | Disponibilidade, separação e consumo de fios e materiais. | Validar movimentações e saldos. |
| Compras e fornecedores | Abastecimento, prazos e informações de materiais. | Apoiar dados de fornecimento e integrações. |
| Expedição e comercial | Compromissos de entrega, prioridades e atendimento ao cliente. | Validar visibilidade de prazos e status. |
| TI e segurança da informação | Infraestrutura, integrações, acessos, suporte e continuidade. | Arquitetar, proteger e sustentar a solução. |
| Consultoria ou fornecedor de software | Configuração, desenvolvimento, migração e suporte especializado. | Entregar escopo contratado e transferir conhecimento. |
| Clientes | Qualidade, prazo e confiabilidade das entregas. | Impactados positivamente; participação conforme necessidade. |
| Órgãos reguladores e auditorias | Conformidade, registros e rastreabilidade aplicável. | Consultados quando houver requisito legal ou contratual. |

---

## 8. Premissas do projeto

Para fins de planejamento, serão assumidas como verdadeiras as seguintes condições:

1. A diretoria disponibilizará um patrocinador com autoridade para priorizar o projeto e resolver conflitos entre áreas.
2. A empresa indicará usuários-chave de PCP, tecelagem, qualidade, manutenção, estoque e TI, com disponibilidade para entrevistas, validações e testes.
3. Os dados mínimos de artigos, fios, teares, receitas, ordens, turnos e paradas estarão disponíveis ou poderão ser saneados durante a implantação.
4. A unidade-piloto possuirá infraestrutura de rede e dispositivos adequados ou terá um plano aprovado para sua disponibilização.
5. As áreas envolvidas participarão da padronização de processos e aceitarão substituir controles paralelos após a validação do sistema.
6. O software poderá ser integrado ao ERP existente por arquivos, APIs ou outro mecanismo tecnicamente viável, sem depender de uma única forma de integração.
7. O piloto será realizado em uma área ou grupo de teares representativo, antes da expansão para toda a operação.
8. Alterações legais, fiscais ou corporativas que não estejam diretamente relacionadas ao PCP serão tratadas como demandas específicas e não interromperão o escopo-base.
9. O projeto terá acesso a ambiente de testes, cópia controlada dos dados e mecanismos de backup conforme a política da empresa.

---

## 9. Restrições do projeto

As principais restrições preliminares são apresentadas a seguir. Elas deverão ser detalhadas no plano do projeto e acompanhadas pelo gerente responsável.

| Categoria | Restrição preliminar |
|---|---|
| Financeira | Orçamento inicial limitado e sujeito à aprovação por etapas; mudanças de escopo poderão exigir nova autorização. |
| Prazo | Necessidade de concluir um piloto em até 8 meses, sem comprometer períodos críticos de produção e fechamento. |
| Recursos humanos | Disponibilidade parcial de usuários-chave; necessidade de equipe com conhecimentos de PCP, tecelagem, dados, UX, integração e suporte. |
| Operacional | Implantação sem interromper a produção; testes e treinamentos deverão respeitar turnos e janelas de manutenção. |
| Dados | Cadastros incompletos, inconsistentes ou com nomenclaturas diferentes poderão limitar a qualidade dos indicadores iniciais. |
| Tecnológica | Dependência de rede, dispositivos no chão de fábrica, políticas de segurança, integrações e compatibilidade com o parque existente. |
| Logística | Diferentes turnos, áreas físicas, níveis de conectividade e necessidade de equipamentos protegidos para ambiente industrial. |
| Escopo | Funcionalidades corporativas não essenciais ao PCP não integram a primeira entrega do sistema de tecelagem. |

---

## 10. Estimativa preliminar de investimentos

A estimativa abaixo é de baixa precisão, destinada à decisão inicial. Os valores devem ser refinados após levantamento de requisitos, definição da estratégia de aquisição ou desenvolvimento e cotação de infraestrutura e serviços.

| Grupo principal | Componentes considerados | Estimativa preliminar |
|---|---|---:|
| Software e serviços especializados | Licença, desenvolvimento/configuração, parametrização, integrações, testes e suporte inicial. | **R$ 120.000 a R$ 220.000** |
| Infraestrutura e dispositivos | Hospedagem ou servidores, rede, terminais, coletores, leitores, impressoras e adequações no chão de fábrica. | **R$ 25.000 a R$ 60.000** |
| Implantação, dados e capacitação | Diagnóstico, saneamento e migração de dados, documentação, treinamentos e acompanhamento do piloto. | **R$ 30.000 a R$ 70.000** |
| Reserva de contingência | Ajustes de escopo, riscos técnicos, reforço de suporte e variações de preços. | **R$ 20.000 a R$ 45.000** |
| **Total preliminar** | **Soma dos quatro grupos principais.** | **R$ 195.000 a R$ 395.000** |

Os valores não incluem, salvo contratação específica, a expansão para múltiplas unidades, substituição integral do ERP, automação física de teares, sensores industriais de grande escala ou obras civis. A aprovação do orçamento deverá considerar o custo total de propriedade, incluindo manutenção, suporte, hospedagem, licenças recorrentes e atualização de dispositivos.

---

## 11. Estimativa de prazo

A estimativa de conclusão do núcleo do projeto é de **8 meses**, contados a partir da autorização formal e da disponibilização da equipe. O prazo pressupõe decisões tempestivas, acesso aos dados, disponibilidade dos usuários-chave e implantação inicial em uma unidade-piloto.

A entrada em produção deverá ocorrer de forma controlada, com treinamento, operação assistida, critérios de aceite e plano de contingência. A expansão para todos os teares e demais áreas da empresa deverá ser reestimada após a avaliação do piloto.

---

## 12. Fatores críticos de sucesso (FCS)

1. **Patrocínio ativo:** a direção deverá comunicar a prioridade do projeto, assegurar recursos e decidir rapidamente sobre conflitos.
2. **Participação do chão de fábrica:** operadores, líderes e supervisores deverão contribuir para que os apontamentos sejam simples e aderentes à realidade.
3. **Processos padronizados:** conceitos como ordem, lote, parada, perda, eficiência, artigo e status deverão ter definições únicas.
4. **Qualidade dos dados:** cadastros, estruturas, receitas, calendários e motivos de parada deverão ser tratados como ativos do projeto.
5. **Escopo controlado:** o núcleo de tecelagem deverá ser entregue antes da incorporação de demandas corporativas amplas.
6. **Usabilidade e disponibilidade:** a solução deverá funcionar com rapidez, poucos passos e adequada ao ambiente de produção.
7. **Integração e governança de TI:** acessos, backups, segurança, logs, suporte e integrações deverão ser definidos desde o início.
8. **Treinamento e gestão da mudança:** cada perfil deverá ser treinado com exemplos da própria operação e acompanhado durante a estabilização.
9. **Medição de resultados:** a linha de base deverá ser registrada para comprovar ganhos de prazo, rastreabilidade, produtividade, perdas e qualidade.
10. **Transferência de conhecimento:** a empresa deverá reduzir a dependência do fornecedor, mantendo documentação, parametrização e equipe interna capacitada.

---

## 13. Principais riscos e oportunidades

| Tipo | Evento | Probabilidade | Impacto | Resposta inicial ou aproveitamento |
|---|---|---|---|---|
| Risco | Dados mestres incompletos ou inconsistentes. | Média | Alto | Criar responsável por dados, regras de saneamento e validação antes do piloto. |
| Risco | Resistência ao apontamento no chão de fábrica. | Média | Alto | Envolver usuários desde o desenho, simplificar telas, treinar e acompanhar por turno. |
| Risco | Integrações com ERP ou equipamentos mais complexas que o previsto. | Média | Alto | Fazer prova técnica no início e manter alternativa por importação/exportação controlada. |
| Risco | Indisponibilidade de usuários-chave por demanda operacional. | Alta | Médio | Reservar agenda, nomear substitutos e formalizar decisões. |
| Risco | Expansão excessiva do escopo para áreas corporativas. | Média | Alto | Separar backlog, aplicar controle de mudanças e priorizar o núcleo de tecelagem. |
| Risco | Conectividade ou dispositivos insuficientes na fábrica. | Média | Alto | Diagnosticar infraestrutura, prever modo de contingência e testar em campo. |
| Risco | Indicadores sem definição comum ou sem linha de base. | Média | Médio | Aprovar dicionário de indicadores e medir situação atual antes da implantação. |
| Risco | Dependência excessiva do fornecedor. | Média | Médio | Exigir documentação, treinamento, acesso a dados e plano de transferência. |
| Oportunidade | Reduzir reprogramações com sequenciamento baseado em capacidade e restrições. | Média | Alto | Priorizar motor de programação e painel de exceções. |
| Oportunidade | Usar dados de paradas e perdas para melhoria contínua e manutenção preventiva. | Média | Alto | Integrar causas, tempos, equipamentos e planos de ação aos indicadores. |
| Oportunidade | Criar rastreabilidade comercial e de qualidade valorizada pelos clientes. | Média | Médio | Disponibilizar consulta de lote e histórico para áreas autorizadas. |
| Oportunidade | Aproveitar a base de dados para futuras integrações corporativas. | Média | Alto | Definir arquitetura modular e backlog de expansão desde o projeto inicial. |
| Oportunidade | Reduzir tempo de reunião e acelerar decisões com gestão à vista. | Alta | Médio | Publicar painéis por perfil e estabelecer rotina de análise. |

Os riscos deverão ser registrados em um instrumento de acompanhamento, com responsável, prazo, gatilho, plano de resposta e status. As oportunidades deverão receber tratamento semelhante, para que não dependam apenas de ações espontâneas.

---

## 14. Macro-cronograma das entregas

O cronograma abaixo utiliza quinzenas sequenciais, sem datas de calendário. A **Quinzena 1** corresponde ao início formal do projeto. As datas reais serão atribuídas após a aprovação deste TAP.

| Entrega principal | Atividades resumidas | Estimativa |
|---|---|---:|
| Mobilização e kickoff | Aprovação do TAP, equipe, governança, plano de comunicação e abertura do projeto. | Quinzenas 1–2 |
| Diagnóstico e levantamento | Mapeamento dos processos de PCP e tecelagem, dores, dados, integrações e linha de base. | Quinzenas 2–4 |
| Visão do produto e requisitos | Priorização do MVP, histórias ou especificações, regras de negócio, indicadores e critérios de aceite. | Quinzenas 4–6 |
| Arquitetura e protótipo | Modelo de dados, perfis, integrações, protótipo de telas e validação com usuários. | Quinzenas 6–8 |
| Cadastros e dados | Saneamento, padronização e carga inicial de artigos, fios, teares, receitas, turnos e parâmetros. | Quinzenas 7–10 |
| Desenvolvimento/configuração do núcleo | Carteira, capacidade, programação, ordens, apontamentos, rastreabilidade, qualidade e indicadores iniciais. | Quinzenas 9–14 |
| Integrações e testes | Integração priorizada, testes funcionais, segurança, desempenho, dispositivos e correções. | Quinzenas 12–15 |
| Treinamento e piloto | Capacitação por perfil, operação assistida, coleta de feedback e ajustes finais. | Quinzenas 14–16 |
| Aceite e encerramento da primeira fase | Aceite formal, relatório de resultados, lições aprendidas, suporte de transição e backlog da expansão. | Quinzena 16 |

A expansão para outros setores e demais teares deverá ser organizada em um novo plano ou em uma fase subsequente, aprovado com base nos resultados do piloto.

---

## 15. Critérios preliminares de aceite e encerramento

O projeto poderá ser considerado apto ao aceite da primeira fase quando o núcleo priorizado estiver disponível no ambiente acordado, os perfis de acesso estiverem configurados, os dados críticos do piloto estiverem validados, os usuários-chave tiverem concluído os testes, os apontamentos essenciais estiverem funcionando, os indicadores definidos forem consultáveis e os defeitos críticos estiverem tratados ou formalmente aceitos.

O encerramento deverá incluir termo de aceite, documentação funcional e técnica, registro de pendências, plano de suporte e sustentação, relatório de indicadores comparando a linha de base com o piloto, lições aprendidas e recomendação sobre a expansão para toda a tecelagem e, posteriormente, para outras áreas corporativas.

---

## 16. Aprovações

| Responsável | Nome | Assinatura | Data |
|---|---|---|---|
| Patrocinador | [Nome e cargo] | __________________________ | ____/____/________ |
| Gerente do projeto | [Nome e cargo] | __________________________ | ____/____/________ |
| Responsável pelo PCP | [Nome e cargo] | __________________________ | ____/____/________ |
| Responsável pela TI | [Nome e cargo] | __________________________ | ____/____/________ |

---

## Observação final

Este TAP é um documento preliminar para autorização e direcionamento. As metas, valores, funcionalidades e prazos deverão ser confirmados durante o diagnóstico e formalizados no plano de gerenciamento do projeto, preservando o foco inicial na tecelagem e mantendo outras integrações corporativas como possibilidades de expansão controlada.


# Análise de Requisitos Funcionais e Não-Funcionais

Identificação dos Requisitos do Sistema Falcão Sombrio para Drones


## Requisitos Funcionais

Descrição do que o sistema **Deve** fazer.


| ID | RF | DESCRIÇÃO |
| ---------- | ----- | ----------- |
|  RF-01        | Autenticação     | O sistema deve permitir que o usuário faça autenticação por biometria e autenticação multifator     |
|  RF-02       | Interface do Sistema     |  O sistema deve ter uma interface para gerenciamento de frotas de drones     |
|  RF-03        | Controle dos Drones |  O sistema deve permitir o controle remoto e autônomo dos drones |
|  RF-04        | Dashboard |  O sistema deve ter um Dashboard em tempo real com telemetria  |
|  RF-05        | Sensores do Drone  |   O sistema deve ter um sensoriamento do ambiente via LIDAR, câmeras e GPS |
|  RF-06        | Resposta |  O sistema deve detectar e evadir de ameaças em tempo real  |
|  RF-07        | Logs  |   O sistema deve Gerar Logs de missões realizadas e eventos críticos|
|  RF-08        | Operação Autônoma |  O sistema deve operar de forma autônoma baseado em redes neurais |
|  RF-09        | Priorização |   O sistema deve ser capaz de priorizar processos conforme a o status crítico da missão |
|  RF-10        | FailOver | O sistema deve suportar failover automático, para quando ocorre falha de servidor |



## Requisitos Não-Funcionais

Descrição de **Como** o sistema deve se comportar


| ID | RNF | DESCRIÇÃO |
| ---------- | ----- | ----------- |
|  RNF-01        | Segurança     |  O sistema deve garantir uma criptografia de ponta e assinaturas digitais     |
|  RNF-02       | Monitoramento    | O sistema deve monitorar processos do SO embarcado, para evitar falhas. O SO embarcado precisa gerenciar múltiplas threads de sensores navegação e IA    |
|  RNF-03        | Armazenamento |   O sistema deve possuir um Banco de Dados NoSQL distribuido para dados em tempo real |
|  RNF-04        | Tolência de Falhas |O sistema deve ter protocolos para a comunicação segura e em tempo real com os drones junto a mecanismos de fallback
|  RNF-05        | Performace   | O sistema não deve sofrer de latência elevada e interrupção de comunicação |
|  RNF-06        | Duração dos Logs | O sistema deve garantir que os Logs sejam altamente disponíveis |




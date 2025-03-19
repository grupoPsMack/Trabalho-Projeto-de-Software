
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



## Requisitos Não-Funcionais

Descrição de **Como** o sistema deve se comportar


- O sistema deve garantir uma criptografia de ponta e assinaturas digitais

- O sistema deve ter protocolos para a comunicação segura e em tempo real com os drones junto a mecanismos de fallback

- O sistema deve monitorar processos do SO embarcado, para evitar falhas. O SO embarcado precisa gerenciar múltiplas threads de sensores navegação e IA,  

- O sistema deve possuir um Banco de Dados NoSQL distribuido para dados em tempo real


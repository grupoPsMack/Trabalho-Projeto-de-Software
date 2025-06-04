# Diagrama de Casos de Uso: Sistema de Gerenciamento de Drones

## Atores

* **Operador Militar:** Usuário principal do sistema, responsável por interagir com os drones.
* **IA do Drone:** Inteligência artificial do drone, responsável por diversas funcionalidades.

## Casos de Uso Principais (Operador Militar)

* **Efetuar Login:**
    * Inclui (<<include>>) **Autorização Multi-Fator** (camada extra de segurança).
      
* **Acessar o Dashboard em Tempo Real:**
    * Visualiza informações e dados dos drones em tempo real.
      
* **Acessar Histórico de Missões:**
    * Revisa missões passadas, logs e dados relacionados.
      
* **Gerenciar a Frota de Drones:**
    * Controla e monitora vários drones.
    * Estende (<<extend>>) **Controlar Drone**.
      
* **Iniciar IA do Drone:**
    * Ativa a inteligência artificial do drone para operações autônomas.
      
* **Controlar Drone:**
    * **Operação Autônoma:**
        * Drone opera de forma independente, guiado pela IA.
        * Inclui (<<include>>) **Gerar Log de Missão**.
    * **Operação Remota:**
        * Operador controla o drone manualmente.
        * Inclui (<<include>>) **Gerar Log de Missão**.
          
* **Gerar Log de Missão:**
    * Registra atividades e dados relevantes durante a missão.
* **Gerar Log de Evento Crítico:**
    * Estende (<<extend>>) **Gerar Log de Missão** para incluir eventos críticos ou falhas.

## Relacionamentos

* **<<include>>:** Um caso de uso é parte integrante de outro.
* **<<extend>>:** Um caso de uso adiciona funcionalidade a outro.

## Resumo

O diagrama descreve um sistema abrangente para gerenciamento de drones, com foco em segurança, controle, monitoramento e registro de dados. Destaca a importância da autenticação segura, operações autônomas e remotas, e logs detalhados para análise e melhoria contínua.



## Casos de Uso Principais (IA do Drone)

* **Monitorar processos do SO embarcado:**
    * Acompanha o funcionamento do sistema operacional do drone.
      
* **Ativar mecanismo de fallback:**
    * Aciona um plano alternativo em caso de falha.
      
* **Reconhecer território hostil:**
    * Identifica áreas perigosas ou não seguras.
      
* **Gerar logs:**
    * Registra informações sobre as operações do drone.
    * Inclui (<<include>>) **Log de Missões**.
    * Inclui (<<include>>) **Log de evento crítico**.
      
* **Detectar ameaças:**
    * Identifica possíveis perigos.
      
* **Evadir ameaça:**
    * Executa ações para evitar ameaças detectadas.
    * Inclui (<<include>>) **Detectar ameaças**.

## Resumo

O diagrama descreve as funcionalidades da IA do drone, incluindo monitoramento, segurança, registro de dados e resposta a ameaças.

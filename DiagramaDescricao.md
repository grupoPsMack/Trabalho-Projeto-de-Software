## Diagrama de Fluxo de Trabalho do Sistema Falcão Sombrio

Este diagrama descreve o fluxo de trabalho do sistema Falcão Sombrio, desenvolvido pela Securus Dynamics, para operações remotas e autônomas de drones bélicos Aquila-X.


![Diagrama de Fluxo de Trabalho do Sistema Falcão Sombrio](data:image/png;base64)


### Seções do Diagrama

1.  **Usuário:**
    * **Introduza a Digital e a Senha:** O ponto de partida, onde o usuário se autentica.
    * **Se a Digital ou Senha Válida:** Indica autenticação bem-sucedida.
    * **Selecione a Função:** Escolha da função do drone para a missão.
    * **Outras Funções Também Podem Ser Selecionadas:** Capacidade de multitarefa.
    * **Interface de Gerenciamento dos Drones:** Controle e monitoramento dos drones.
    * **Operação Autônoma:** Controle por IA.
    * **Operação Remota:** Controle manual.
    * **Tentativas Falhas:** Registro de tentativas de autenticação inválidas.
    * **Não Existem Tentativas:** Indica que não houve tentativas de autenticação falhas.
2.  **Missões:**
    * **Deleção de Amigos (Opcional):** Restrição de acesso a outros operadores.
    * **Log da Missão:** Registro detalhado da missão no BD.
    * **Fim da Função:** Conclusão da operação do drone.
3.  **Interface:**
    * Fornece a interface para interação do usuário com o sistema.

### Descrição Detalhada

O processo começa com a autenticação do usuário, que insere digital e senha. Após a autenticação, o usuário seleciona a função do drone e o opera remotamente ou por IA. A deleção de amigos (opcional) restringe o acesso. Todas as ações são registradas no BD.

### Considerações

* A autenticação é o ponto de partida, garantindo segurança.
* A flexibilidade é mantida com múltiplas funções e modos de operação.
* O registro detalhado no BD é crucial para auditoria.

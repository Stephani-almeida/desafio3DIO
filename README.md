## Desafio DIO: Criação de um Banco de Dados SQL no Azure

O objetivo deste desafio foi aplicar os conhecimentos adquiridos sobre a plataforma Azure para provisionar um Banco de Dados SQL. A abordagem adotada visa simular a criação de um banco de dados para uma pequena empresa, priorizando um baixo custo e utilizando as recomendações do Copilot do Azure.

### Processo de Criação do Banco de Dados SQL:

**Início da Criação do Banco de Dados SQL:**
A navegação foi iniciada através do portal Azure, acessando a seção de "Bancos de Dados SQL" e optando por "Criar banco de dados SQL".

**Configurações Básicas (Detalhes do Projeto e Banco de Dados):**
* **Assinatura:** "Assinatura do Azure 1" foi selecionada.
* **Grupo de recursos:** O grupo de recursos "DIO-LAB01" foi escolhido.
* **Nome do banco de dados:** O banco de dados foi nomeado como "DesafioDIO-SQL".
* **Servidor:** Um novo servidor foi criado com o nome "desafiodio-sql-server".
    * **Localização:** "East US" foi selecionada.
    * **Método de autenticação:** "Usar autenticação SQL e autenticação do Azure Active Directory" foi escolhido.
    * **Logon do administrador do servidor:** "azureadmin" foi definido.
    * **Senha:** Uma senha segura foi configurada.
* **Você deseja usar um pool elástico?** Não.
* **Carga de trabalho:** "Desenvolvimento/Teste".
* **Configurar banco de dados:**
    * **Modelo de compra:** "Básico" (para baixo custo) foi selecionado.
    * **Tamanho do armazenamento máximo:** "2 GB".
    * **Número máximo de vCores/DTUs:** "5 DTUs".

**Configurações de Rede:**
* **Método de conectividade:** "Ponto de extremidade público".
* **Permitir que os serviços e recursos do Azure acessem este servidor:** Sim.
* **Adicionar o endereço IP do cliente atual:** Sim (para facilitar a conexão inicial).

**Configurações de Segurança:**
* **Habilitar o Microsoft Defender para SQL:** "Básico (gratuito)" foi selecionado.
* **Habilitar o Ledger:** Não.

**Configurações Adicionais:**
* **Agrupamento:** "SQL_Latin1_General_CP1_CI_AS" foi mantido como padrão.
* **Backup e replicação de dados:**
    * **Redundância de armazenamento de backup:** "Armazenamento com redundância local (LRS)".
* **Manutenção de janelas:** "Sistema gerenciado".

**Configurações de Marcas (Opcional):**
Nenhuma marca foi adicionada neste desafio.

**Revisão e Criação:**
Após a revisão de todas as configurações, a validação do banco de dados "passou", estabelecendo que as configurações eram corretas para a criação. O banco de dados SQL foi então criado e provisionado com sucesso.

---

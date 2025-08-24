# Lab Azure: Configuração de Instância de Banco de Dados

## Entendendo o Desafio
Este laboratório tem como objetivo **praticar a configuração de uma instância de Banco de Dados** na plataforma Microsoft Azure. O desafio consiste em criar um repositório contendo resumos, anotações e dicas sobre o uso do Azure, servindo como material de apoio para estudos e futuras implementações.

## Objetivos de Aprendizagem
Ao concluir este desafio, você será capaz de:  
- Aplicar os conceitos aprendidos em um ambiente prático;  
- Documentar processos técnicos de forma clara e estruturada;  
- Utilizar o GitHub como ferramenta para compartilhamento de documentação técnica.

## 1. Criação de Conta no Azure
Antes de configurar bancos de dados, é necessário criar uma conta no Azure:  
- Acesse [Microsoft Azure](https://azure.microsoft.com/) e clique em **Iniciar gratuitamente**.  
- Preencha os dados pessoais e informações de pagamento (verificação de identidade).  
- Após criar a conta, você terá acesso ao **Portal Azure** e créditos gratuitos para explorar os serviços.

## 2. Configurações Iniciais
- **Assinaturas (Subscription):** Define a cobrança e acesso aos recursos.  
- **Grupos de Recursos:** Organizam recursos relacionados, facilitando a gestão.  
- **Região:** Escolha a localização geográfica para alocação dos recursos.  
- **Preferências do Portal:** Personalize o dashboard e o tema (claro/escuro).

## 3. Criando uma Instância de Banco de Dados
Para criar uma instância de banco de dados no Azure, siga os passos:  

1. **Acessar o Portal Azure:** Entre no [Portal Azure](https://portal.azure.com/).  
2. **Criar um Novo Recurso:** Clique em **Criar um recurso** → **Banco de Dados** → escolha entre **SQL Database** ou **Azure Database for MySQL/PostgreSQL**.  
3. **Configurações Básicas:**  
   - Nome do banco de dados  
   - Assinatura e grupo de recursos  
   - Região de implantação  
   - Tipo de servidor e versão do banco  
4. **Configurações de Performance e Armazenamento:**  
   - Escolha tamanho de CPU, memória e armazenamento  
   - Configure backup automático e redundância, se necessário  
5. **Revisar e Criar:**  
   - Confirme todas as configurações e clique em **Criar**  
   - Aguarde a implantação ser concluída  
6. **Acessando a Instância:**  
   - Utilize ferramentas como **Azure Data Studio**, **SQL Server Management Studio** ou clientes MySQL/PostgreSQL para se conectar à instância.

> **Dica:** Use **grupos de recursos e tags** para organizar os bancos de dados por projeto, ambiente ou finalidade.

## 4. Filtros e Organização de Recursos
- Utilize **tags** para facilitar a gestão e relatórios.  
- Use filtros do portal para localizar rapidamente instâncias de banco de dados.  
- Agrupe recursos relacionados para simplificar o monitoramento e a manutenção.

## 5. Aprendizado Obtido
Durante o laboratório, foi possível compreender:  
- Criação e configuração de contas no Azure;  
- Organização de recursos com grupos e tags;  
- Passo a passo para criação de instâncias de banco de dados SQL, MySQL ou PostgreSQL;  
- Configurações de performance, armazenamento e backup;  
- A importância de monitorar e organizar recursos para facilitar futuras implementações.

## Referências
- [Portal Microsoft Azure](https://portal.azure.com/)  
- [Documentação Oficial Azure - SQL Database](https://docs.microsoft.com/azure/azure-sql/)  
- [Documentação Oficial Azure - MySQL/PostgreSQL](https://docs.microsoft.com/azure/azure-database/)

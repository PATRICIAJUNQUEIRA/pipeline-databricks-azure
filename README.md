# Pipeline-Databricks-Azure

Este projeto tem como objetivo criar e automatizar uma pipeline de dados no ambiente Azure para uma base de dados de imóveis. A pipeline é estruturada em três camadas: unbound, silver e gold, proporcionando um fluxo de dados consistente e de qualidade. Além disso, é configurada uma trigger para executar a pipeline a cada hora.

## Conteúdo do Projeto

### 1. Criação de Recursos na Nuvem da Azure
   - Configuração e provisionamento de recursos necessários no ambiente Azure para suportar a pipeline.

### 2. Construção de um Data Lake
   - Implementação de um Data Lake para armazenamento eficiente e escalável dos dados de imóveis.

### 3. Utilização da Linguagem Scala no Databricks
   - Desenvolvimento de scripts e notebooks utilizando Scala no ambiente Databricks para processamento e transformação dos dados.

### 4. Conexão de Aplicativos aos Serviços Azure
   - Estabelecimento de conexões entre aplicativos e serviços Azure para integrar diferentes componentes da pipeline.

### 5. Gerenciamento de Pipelines com Data Factory
   - Utilização do Azure Data Factory para orquestrar e gerenciar o fluxo de dados entre as diferentes camadas da pipeline.

### 6. Colocação do Pipeline em Produção
   - Configuração e implantação do pipeline em ambiente de produção, garantindo a execução automática e confiável.

## Arquitetura do Projeto

![Diagrama sem nome drawio](https://github.com/PATRICIAJUNQUEIRA/pipeline-databricks-azure/assets/96187596/6b25fb59-b8a2-47fe-a30d-6f136096f865)


A imagem acima representa a arquitetura geral do projeto, destacando a interação entre os diferentes serviços na nuvem Azure, o fluxo de dados entre as camadas e a trigger configurada para execução periódica.

## Detalhes da Trigger e Funcionalidades do Pipeline

- **Trigger a Cada Hora:**
  - A pipeline é acionada automaticamente a cada hora, garantindo atualizações frequentes e regulares no banco de dados de imóveis.

- **Funcionalidades do Pipeline:**
  - **Unbound:**
    - Captura e ingestão de dados brutos.
  
  - **Silver:**
    - Processamento e transformação dos dados brutos.
    - Padronização e limpeza dos dados.

  - **Gold:**
    - Modelagem e estruturação final dos dados.
    - Preparação dos dados para análises avançadas.

## Como Contribuir

1. Faça um fork do repositório.
2. Crie uma branch para sua feature: `git checkout -b feature-nova`.
3. Faça o commit das suas alterações: `git commit -m 'Adiciona nova feature'`.
4. Faça o push para a branch: `git push origin feature-nova`.
5. Abra um Pull Request.

**Dúvidas ou Sugestões?** Sinta-se à vontade para abrir uma issue ou entrar em contato. Seu feedback é muito bem-vindo!

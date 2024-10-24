# Integração de Sistemas de Informação

Este projeto foi desenvolvido no âmbito da disciplina de **Integração de Sistemas de Informação (ISI)** da **Escola Superior de Tecnologia do IPCA**, com o objetivo de implementar um processo ETL (Extract, Transform, Load) utilizando a ferramenta KNIME. O foco é a integração de dados de diferentes formatos e fontes, com vista à análise e à tomada de decisões numa empresa de produção de bobines.

## Enquadramento

A empresa de produção de bobines enfrenta dificuldades em lidar com a grande quantidade de dados dispersos em diferentes formatos (CSV, Excel, JSON, XML). Este projeto visa resolver esse problema ao consolidar os dados e facilitar a sua análise através de dashboards e relatórios.

## Objetivo

Demonstrar como a aplicação de processos ETL pode melhorar a análise e utilização de dados, agregando, limpando e transformando os mesmos para suportar a tomada de decisões empresariais.

## Tecnologias Utilizadas

- **KNIME**: Ferramenta low-code para construção de fluxos ETL.
- **CSV, Excel, JSON, XML**: Formatos de ficheiros de entrada.
- **Google Sheets**: Integração para sincronização de dados.
- **REST API**: Utilizada para obter dados externos via GET Request.
- **Base de dados**: Sincronização com base de dados SQL server.
- **Email**: Envio de alertas automáticos.

## Fluxo ETL

1. **Extração (Extract)**:
   - Leitura de ficheiros CSV, Excel, e pedidos GET de APIs.
   - Extração de dados a partir de ficheiros XML.

2. **Transformação (Transform)**:
   - Limpeza e agregação de dados.
   - Manipulação de strings e datas, anonimização de dados sensíveis.
   - Conversões e filtragem de dados.

3. **Carga (Load)**:
   - Visualização de dados através de dashboards interativos.
   - Exportação para Google Sheets.
   - Geração de relatórios e gráficos.

## Principais Funcionalidades

- **Anonimização de dados**: Utilização de técnicas de salting para proteger informações sensíveis.
- **Dashboards**: Geração de gráficos e tabelas para facilitar a análise visual.
- **Automatização**: Processos automatizados para integração contínua e envio de alertas via email.
- **Manipulação de Strings**: Utilização de expressões regulares para extrair e manipular informações.

## Estrutura do Projeto

- `/data`: Ficheiros de exemplo utilizados no processo ETL (CSV, Excel, XML, JSON).
- `/src`: Fluxos KNIME desenvolvidos para o projeto.
- `/docs`: Documentação adicional e relatórios.
- `/output`: Dashboards e ficheiros de saída gerados pelo processo ETL.

## Como Executar

1. **Instalar KNIME**: [Download KNIME](https://www.knime.com/downloads)
2. **Carregar o Fluxo de Trabalho**: Importa os ficheiros KNIME presentes na pasta `/src`.
3. **Executar o Fluxo ETL**: Configura as fontes de dados e executa o processo de ETL no KNIME.
4. **Gerar Dashboards**: A partir dos dados processados, os dashboards são gerados automaticamente.

## Conclusão

Este projeto mostrou a eficácia da utilização de uma plataforma low-code como o KNIME para realizar processos ETL e integrar dados de diferentes fontes, garantindo maior eficiência e apoio à decisão numa empresa. As funcionalidades implementadas, como a anonimização de dados e a geração de dashboards, são cruciais para a segurança e análise dos dados empresariais.

## Bibliografia

- [KNIME Documentation](https://docs.knime.com/)

## Autor

Pedro Silva

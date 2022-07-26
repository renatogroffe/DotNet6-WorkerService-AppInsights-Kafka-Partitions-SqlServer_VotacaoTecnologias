# DotNet6-WorkerService-AppInsights-Kafka-Partitions-SqlServer_VotacaoTecnologias
Exemplo de consumo de mensagens de um tópico do Apache Kafka com votos de uma enquete sobre tecnologias em um Worker Service criado com .NET 6, utilizando ainda SQL Server + Dapper.Contrib para gravação dos dados (registrando inclusive as partições de origem) e um Dockerfile para geração de imagens Docker em Linux. Inclui monitoramento via Azure Application Insights.

Aplicação para geração dos eventos:

**https://github.com/renatogroffe/ASPNETCore6-MVC-AzureEventHubs-Kafka-AppInsights_SiteQuestao**
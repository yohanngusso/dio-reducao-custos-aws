# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

> Desafio do Bootcamp **GFT Start #7 - Java** da plataforma [DIO (Digital Innovation One)](https://www.dio.me/).
> O objetivo deste desafio é elaborar um relatório de implementação de serviços AWS, identificando 3 serviços que possam gerar redução de custos imediatos para uma empresa fictícia.

---

Empresa: Future Industries
Responsável: Yohann

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Future Industries, realizado por Yohann. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:
- Amazon EC2 Auto Scaling
- Otimização do uso de servidores e capacidade computacional
- A Future Industries mantinha servidores provisionados para atender picos de demanda, resultando em recursos ociosos durante períodos de baixa utilização. Com o EC2 Auto Scaling, a infraestrutura escala automaticamente conforme a demanda real, adicionando instâncias em momentos de pico e removendo quando ociosas. Isso elimina o desperdício com servidores subutilizados e reduz custos de computação em até 60%.

Etapa 2:
- Amazon S3 (Simple Storage Service)
- Armazenamento escalável de baixo custo
- A empresa utilizava servidores locais para armazenamento de documentos, backups e arquivos históricos, gerando altos custos com manutenção de hardware e espaço físico. Com a migração para o Amazon S3, os dados são armazenados na nuvem com alta durabilidade e disponibilidade. Utilizando as classes de armazenamento S3 Intelligent-Tiering e S3 Glacier para dados acessados com menor frequência, a empresa reduz significativamente os custos de armazenamento.

Etapa 3:
- AWS Lambda
- Computação serverless sob demanda
- Diversos processos internos da Future Industries, como geração de relatórios, processamento de dados e integrações entre sistemas, rodavam em servidores dedicados 24/7 mesmo sendo executados apenas periodicamente. Com o AWS Lambda, esses processos são executados sob demanda, sem necessidade de provisionar ou gerenciar servidores. A cobrança é feita apenas pelo tempo de execução real, eliminando custos com infraestrutura ociosa.

## Conclusão
A implementação de ferramentas na empresa *Future Industries tem como esperado a redução de custos operacionais com infraestrutura, a eliminação de desperdício com recursos ociosos e a modernização dos processos internos*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

- Documentação oficial do Amazon EC2 Auto Scaling
- Documentação oficial do Amazon S3
- Documentação oficial do AWS Lambda
- Planilha comparativa de custos antes e após a implementação


---

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.


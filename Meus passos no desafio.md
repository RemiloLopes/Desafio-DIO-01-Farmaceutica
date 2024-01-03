# Analisar a informação

## Informações que temos
- Farmaceutica com 0 de Cloud e quer entrar na Cloud
- É uma empresa vendedora B2B, um HUB de distribuição para outras empresas
- O objetivo é reduzir os custos de Cloud
- Devo fornecer 3 ferramentas AWS para ajudar a empresa a melhorar a eficiência e reduzir custos

## Informações que não temos
- Tamanho da empresa
- Quantidade de clientes
- Raio de atendimento aos clientes
- Nacional ou multinacional
- Carga computacional média da empresa
- Fluxo médio de dados da empresa

## Conclusão a partir disso
Como não sabemos nada sobre as operações da empresa, sua clientela e etc. vamos priorizar o baixo custo e visar a eficiência equivalente a uma empresa pequena ou média.
O desafio provavelmente é feito com baixo nível de complexidade para que o foco seja a definição e explicação das ferramentas escolhidas.

# O Plano
A parte 1 do plano é definir quais tipos de serviço são essenciais para menter as operações da empresa.
A parte 2 do plano é definir qual serviço de cada tipo é o mais adequado para o nosso objetivo.

## Parte 1
O que uma empresa B2B precisa?
- Computação para processamento de dados, tanto da empresa quanto dos clientes
- Banco de dados para pesquisas e cruzamento de dados com segurança
- Serviço de armazenamento para *armazenar* :D

## Parte 2
Quais são os serviços mais adequados dessas respectivas áreas?
- Amazon Elastic Compute Cloud (EC2): O EC2 fornece capacidade de computação sob demanda, o que é essencial para uma empresa farmacêutica B2B que precisa escalar rapidamente para atender a demanda.
- Amazon Relational Database Service (RDS): O RDS fornece bancos de dados relacionais gerenciados, o que é ideal para uma empresa farmacêutica B2B que precisa de um banco de dados seguro e confiável para armazenar dados confidenciais.
- Amazon Simple Storage Service (S3): O S3 fornece armazenamento de objetos escalável e durável, o que é necessário para uma empresa farmacêutica B2B que precisa armazenar grandes quantidades de dados, como imagens de produtos, documentos e arquivos de log.
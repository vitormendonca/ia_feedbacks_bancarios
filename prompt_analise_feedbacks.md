# Análise Técnica de Insights de Feedbacks de Clientes Bancários

## O Quê

Preciso de uma análise técnica dos Insights de feedbacks de clientes bancários. Extraia e analise os insights dos feedbacks extraídos.

Contexto: estou trabalhando com feedbacks de clientes bancários relacionados a novo produto de investimento dentro do aplicativo para dispositivos móveis.

## Finalidade

O resultado será usado pela equipe interna para compreensão clara e finalmente otimização ou alteração para uma nova versão corrigida e melhorada para experiência dos clientes.

## Como

### Dados Disponíveis

A base contém:
- Nomes (Nome e Sobrenome)
- Ratings de qualidade por estrelas
- Texto de feedback

### Critérios de Análise

A IA deve classificar os feedbacks por polo, insights negativos e positivos com critério de urgência e recorrência. Incluir quantidade de usuários com mesma reclamação no caso de insights negativos.

Caso cliente dê dois dados de polo diferente (exemplo: um insight negativo e um positivo), separe-os e trate-os como individuais.

## Cuidados e Restrições

- Use apenas os dados fornecidos
- Não invente números, causas ou conclusões
- Não exponha dados pessoais ou sensíveis
- Se houver informação insuficiente, indique a limitação
- Use linguagem simples no pdf

## Entrega e Formato

### Primeiro Arquivo: Insights_Feedbacks.pdf

Entregue em um formato pdf estruturado e editado contendo duas listas:

Uma com feedbacks positivos e sua frequência com dados detalhados com o nível de qualidade, estrelas dadas por exemplo, e quantidade de usuários com a mesmo insight.

Uma lista com insights negativos, qualidade de rating dada e quantidade de usuários por insight.

As listas devem ser crescentes e consecutivas baseadas na quantidade identificada.

### Segundo Arquivo: Analise_Detalhada_Insights.xlsx

Entregue em outro arquivo xlsx com 2 tabelas detalhadas: uma de insights positivos e outro de negativos.

Devem conter qualidade do rating, quantidade de clientes por insight. Devem ser crescentes e consecutivas baseadas na quantidade identificada.

### Terceiro Arquivo: Plano_Acao_Recomendacoes.pdf

Finalmente entregue um arquivo pdf com as ações recomendadas para cada insight negativo e o motivo, assim como comentário e possível otimização dos insights positivos, foco na finalidade descrita.

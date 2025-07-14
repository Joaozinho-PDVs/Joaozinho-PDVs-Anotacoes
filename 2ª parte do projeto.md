# Quadro "É, não é"

| É                                                                                         | NÃO É                                                                                                                                                                              |
| ----------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Sistema simples de gerenciamento de fluxo de caixa e estoque de uma conveniência familiar | SaaS ou sistema que pode ser incorporado em cenários muito diferentes de uma conveniência                                                                                          |
| Ferramenta simples, mas que consegue substituir planilhas ou outros sistemas manuais      | Um ERP (Enterprise Resource Planning) sistema de gerenciamento completo responsável por como finanças, recursos humanos, produção, logística, vendas, entre outras funcionalidades |
| Sistema web                                                                               | App mobile ou para PC                                                                                                                                                              |
|                                                                                           | Sistema de gerenciamento de qualidade e/ou integridade dos produtos                                                                                                                |

| Faz                                                                                                                                                                                                                                      | Não faz                                                                                  |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| Registra vendas de produtos e aglomera os produtos de cada venda em uma lista de itens com o valor de cada item, quantidade e total da venda                                                                                             | Não emite notas fiscais eletrônicas, nem faz integração bancária                         |
| Exibe um dashboard com um gráfico com o número de vendas na semana separado por colunas de cada dia, outro gráfico com todas a soma do valor de todas as vendas de cada dia da ultima semana e uma lista dos itens que estão sem estoque | Não faz cálculos de impostos ou lucros                                                   |
| É possível adicionar, ler, editar e deletar produtos através da página de estoque e cada produto terá seu nome, descrição, quantidade, valor, código, tag e status                                                                       | Não guardará informações mais precisas dos produtos, como validade ou tabela nutricional |
| Exibe uma página para visualização de todo o histórico de vendas, com detalhamento dos dados da venda                                                                                                                                    | Não faz previsões de vendas                                                              |

# Estórias dos usuários

## 1 - Venda no caixa

Joãozinho é responsável pelo caixa e aparece um cliente para passar as compras. Ele então, inicia uma venda no sistema podendo usar o leitor de código de barras ou adicionando o produto manualmente. Após todos os produtos passarem, ele fecha o registro da venda.

## 2 - Conferindo receita e estoque

Seu André, dono do estabelecimento, vai no fim de semana conferir a receita da semana, a movimentação de clientes na loja e ver quais itens estão fora de estoque, para repor o estoque.

## 3 - Adicionando itens ao estoque

Seu André, após comprar itens que estavam em falta e novos itens, ele vai ao sistema e cadastra os novos itens e adiciona a quantidade dos itens que estavam em falto no estoque.

## 4 - Acessando histórico de vendas

Seu André, curioso em saber mais detalhadamente como foram das vendas de determinado dia, vai no histórico e analisa todas as compras do dia, vendo informações mais detalhadas e específicas de cada venda.

# Diagramas de casos de uso

## 1 - Fazendo uma venda

![1 - Atendimento ao caixa](Excalidraw/1\ -\ atendimento\ ao\ caixa.excalidraw.png)

## 2 - Acessando o Dashboard para analisar informações

![[2 - Analizando dados da semana.excalidraw]]

## 3 - Gerenciamento de estoque

![[3 - Gerenciamento do estoque.excalidraw]]

## 4 - Acesso ao histórico de vendas

![[4 - Visualização de vendas.excalidraw]]

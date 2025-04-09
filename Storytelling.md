#Programação #ProgramaçãoAvançada 
Data: 2025/03/31

## Contexto
Era uma vez, uma conveniência que vendia diversos produtos e funcionava 24 hrs por dia. Todos os produtos dessa conveniência tinham códigos de barra únicos para cada produto e a conveniência tinha um computador com internet no caixa para dar baixa nos produtos manualmente em uma planilha. Isso fazia com que fosse muito trabalhoso o registro das vendas e do estoque da conveniência, causando lerdeza na fila do caixa e acumulo de tarefas, ou seja, muito tempo gasto para pouco resultado.

## Motivações
Essa conveniência era um empreendimento familiar, então, João, filho do dono, que ficava no caixa e era aluno do professor Hertz de Programação Avançada e engenharia de software, viu que apesar de funcionar o fluxo de trabalho, existiam formas alternativas mais práticas e eficientes de fazer o gerenciamento do caixa utilizando linguagens de programação e frameworks, aumentando a produtividade e diminuindo a lerdeza na fila. 

## Objetivos
Com isso em mente, João viu que seus objetivos eram claros:
- Fazer uma interface gráfica que conseguisse:
	- Ser prática e útil no dia-a-dia da empresa, de modo a simplificar processos manuais de entrada do número de vendas e estoque da conveniência
	- Ter sua exibição das vendas e do estoque mais amigável e com uma experiência mais proveitosa para o usuário do que simplesmente uma planilha 
	- Simplificação e segurança na gerencia e exposição dos vendas e estoque
- Fazer uma API Rest com conseguisse:
	- Ser simples, rápida e escalável
	- Possibilidade de ser integrada com outras tecnologias (Ex: Grafana)

## Tecnologias
Para este projeto, João escolheu  as seguintes tecnologias para o Front-end e o Back-end.
#### Front-end
- [NEXT.JS](https://nextjs.org/) 
	- Framework derivado do React para aplicações [Single Page Application](https://nextjs.org/docs/app/building-your-application/upgrading/single-page-applications) (SPA)
	- Tem um ótimo [gerenciamento de rotas](https://nextjs.org/docs/app/getting-started/layouts-and-pages) 
	- Suporte a Componentes [Server Side Rendering](https://nextjs.org/docs/app/building-your-application/rendering/server-components) (SSR) e [Client Side Rendering](https://nextjs.org/docs/app/building-your-application/rendering/client-components) (CSR)
	- Suporte a programação assíncrona para leitura e gravação de dados
- [Material UI (MUI)](https://mui.com/material-ui/getting-started/)
	- Framework React para componentes pré-prontos
	- Diversidade de inúmeros componentes para situações diversas
	- Gráficos 
	- Rapidez de estilização
- [PenPot](https://penpot.app/) 
	- Plataforma colaborativa de design gráfico
	- Figma-like
	- Open-Source
#### Back-end
- Django
	- Framework Python para criação de aplicações Web
	- Utilização de diversos sub-frameworks
	- Sub-framework Django Rest Framework para criação de REST APIs
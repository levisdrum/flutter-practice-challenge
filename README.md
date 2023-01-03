# ROTEIRO TESTE FLUTTER GB
Bem-vindo ao teste prático para os candidatos ao cargo de desenvolvedor flutter no GB.



## OBJETIVO
Nosso objetivo com este passo do processo de recrutamento é conhecer melhor as suas habilidades técnicas.

Com isso, selecionamos um desafio para você que irá prepará-lo melhor para enfrentar o nosso dia a dia.



## REQUISITOS DA ENTREGA
Gostaríamos nos entregasse uma aplicação utilizando a api do GITHUB https://developer.github.com/v3/ consumindo os seguintes endpoints:

Endpoint user: https://api.github.com/users/USER_GITHUB
Endpoint repos: https://api.github.com/users/USER_GITHUB/repos
Endpoint starred: https://api.github.com/users/USER_GITHUB/starred{/owner}{/repo}



### A aplicação deverá constituir três componentes principais:
1 - O campo de busca.
2 - Visualização de resultados.
3 - Dois botões para executar um determinado resultado ex: botão repositorio; botão de starred.



### Descrição dos critérios: 
1 - Ao clicar nos botões de repos e starred, deverá mostrar uma lista simples de cada endpoint apresentado anteriormente.

2 - Dado um determinado usuário, deverá ser possível navegar diretamente até a página de detalhe do usuário sem que seja necessário efetuar uma nova busca.

3 - Gostariamos de pesquisar por usuario.
4 - Gostariamos de ao clicar no botão de repos, listar repositorios do usuario pesquisado.
5 - Gostariamos de ao clicar no botão de starred, listar os repositorios mais visitados por aquele usuario.
6 - Você poderá usar o framework flutter UI ou Materialize para construção dos componentes (Se preferir, os componentes poderão ser criados do zero, utilizando as boas práticas: reutilização, acessibilidade e performance).
7 - Gostariamos que pudesse fazer testes unitarios na aplicação.



### STACK ESPERADA PARA O TESTE
1 - Flutter 



### CENÁRIO
Na página do campo de busca, deverá ser possível inserir nomes de usuários do github, repositórios e os mais visitados pelos os usuários.



## AVALIAÇÃO
A avaliação será feita da seguinte forma:

1 - Vamos analisar e compilar o seu código;
2 - Rodar sua aplicação e executar testes para validar o atendimento funcional dos itens acima;
3 - Verificar se o seu código é limpo (Clean Code), fácil de entender e de dar manutenção;
4 - Durante entrevista, simularemos uma revisão do seu código, percorremos o código junto com você para discutirmos sobre suas decisões de implementação, os pontos positivos e negativos;



### DICAS:
Tenha em mente que o seu avaliador irá executar o código antes de falar com você;
Procure fazer uma entrega simples mas consistente, usando a experiência e conhecimento adquiridos durante sua carreira;
Não se preocupe em entregar algo extremamente completo ou rebuscado, não vamos usar este código em produção;
Tudo será avaliado, dê o seu melhor!

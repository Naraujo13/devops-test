#  Teste para DevOps - Indeorum

## Introdução
A indeorum iniciou como uma empresa voltada a serviços de data science aplicados a pós-graduação brasileira.
Por isso, seus três produtos lançados são voltados para esta área (Cientum, Ranquium e Quantum).
A necessidade de escalonar estas aplicações conforme aumenta o número de usuários é uma prioridade atual da empresa e caso selecionado você se encontrará em uma posição privilegiada frente a esta necessidade latente.

## Objetivo do Teste

Como membro da equipe Indeorum, você será solicitado para projetar e manter arquiteturas para novas aplicações. Para este teste, a equipe solicitou acesso a uma aplicação que utilize Ruby on Rails, com banco de dados MongoDB, motor de busca ElasticSearch e com Nginx para balanceador de acesso. A equipe deseja também conseguir visualizar os dados de busca em uma dashboard e sugeriu a utilização do Kibana. 

Sua tarefa será projetar estra estrutura utilizando-se de Docker e alguma ferramenta de orquestração de containers, como Kubernetes ou Docker Swarm. Além disso, também é muito importante a integração com um serviço de controle de acesso como o NewRelic ou Rollbar. Esta aplicação deverá ser hospedada para fins deste teste em modo de produção em algum serviço gratuito como Amazon AWS, GoogleCloud, Heroku e etc.

Posteriormente, disponibilizar um projeto de teste de carga/stress sobre esta aplicação, propondo um modelo de monitoramento para a mesma. 

Também é obrigatória a disponibilização de um Readme (em formato markdown) com instruções para o deploy da aplicação.

O principal objetivo desta etapa é verificar como é a sua organização e projeto de containeres visando a escalabilidade facilitada da aplicação, queremos visualizar como você se organiza e como soluciona a integração entre as diversas aplicações apresentadas.

## Requisitos

- Utilização de Docker
- Containers para ElasticSearch, MongoDB, Nginx, Kibana e Rails integrados
- Orquestração dos containeres utilizando o Kubernetes ou Docker Swarm
- Deploy da aplicação em modo produção em um servidor de hospedagem (Amazon, Google Cloud, Softlayer, Heroku...)
- Projeto de teste de carga e modelo para monitoramento
- Readme(Markdown format) com  para deploy

## Extras

- Escalabilidade e distribuição de carga automática (tanto para mais quanto para menos) do Nginx
- Escalabilidade e distribuição de carga automática (tanto para mais quanto para menos) do MongoDB

## Entregáveis/Apresentação

Para execução do teste, deverá ser realizado o fork deste repositório e desenvolvido a partir de então. A entrega deverá ser realizada através do envio do link do repositório para o email até **sexta-feira (22/02/19), as 23:59**. No **sábado, dia 23/02/19, às 14h**, será realizada uma etapa presencial consistindo de uma etapa em grupo, além de uma breve apresentação individual do resultado enviado deste teste.

## Dicas e Sugestões:

- O Docker Compose facilita a composição de volumes, use ele a seu favor
- Não esqueça de criar volumes e redes compartilhadas entre os containers
- Priorize imagens oficiais sempre, procurando por elas no DockerHub

## Links úteis

- [DockerHub](https://hub.docker.com/)

- [Docker](https://www.docker.com/)

- [Docker-Compose](https://docs.docker.com/compose/)

- [Kubernetes](https://kubernetes.io/)

- [Nginx](https://www.nginx.com/)

- [ElasticSearch](https://www.elastic.co/)

- [Kibana](https://www.elastic.co/products/kibana)

- [MongoDB](https://www.mongodb.com/)

- [Ruby on Rails](https://rubyonrails.org/)

- [New relic](https://newrelic.com/)

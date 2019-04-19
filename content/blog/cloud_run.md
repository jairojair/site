---
title: Google Cloud Run
slug: google-cloud-run
date: 2019-04-14
description: Artigo sobre google cloud run, a solução de serverless agnostica do google.
tags: pt-br, docker, serverless
draft: true
---

#### O serverless do seu jeito!

Serverless deixou de ser um buzzword para ser uma realidade já faz algum tempo. Vide exemplo os cases apresentados pelos grandes players do mercado de Cloud.

O conceito é relativamente simples, cada requisição é tratada de forma isolada.

Exemplo:

    > Image serverless flow

Já faz algum tempo que estou estudando soluções serverless agnosticas a uma linguagem de programação, cenário que as vezes se faz necessário quando você tem uma stack fora do convencial Java, Node, Python, Ruby, Go etc.

A propria solução atual do Google chamada [Cloud Functions][cf] só suporta Node, Go e Python. [Azure][az] e [AWS][aws] vão na mesma pegada.

Já o [Cloud Run][cr] tenta resolver esse problema com outra abordagem, permitindo você definir uma imagem docker que será usada para processar o request em questão.

  > Image cloud run


#### Habilitando cloud run na sua conta do GCP

Lorem ipsum, vai que da!

#### Dockerizando sua aplicação

Vamos adicionar nossa aplicação no docker.

```Dockerfile

FROM platform:version-alpine

RUN apk add --update \
  make

RUN install deps

```

#### Rodando

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.

#### Testando

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.

#### Conclusão

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


Tips:

Ver doc official

Mostrar os 3 passos (Dockerfile, Build, Run)


[gcp]: https://cloud.google.com
[aws]: https://aws.amazon.com/pt/lambda
[cr]: https://cloud.google.com/run
[cf]: https://cloud.google.com/functions
[az]: https://azure.microsoft.com/pt-br/services/functions

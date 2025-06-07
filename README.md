# TesteTecnicoPandaVideo
Teste Técnico Panda Video


# Teste Técnico Panda Video

Nesse teste será avaliado a familiaridade e capacidade do candidato de produzir um código
limpo e escalável em cima das nossas tecnologias mais usadas no dia a dia.

## Referências

[Panda Video API](https://pandavideo.readme.io/reference/list-videos) Criar uma conta trial na panda vídeo para fazer o teste é essencial. Pode ficar
tranquilo(a) que não cobramos nada durante o trial
[VueJS](https://vuejs.org/)
[Vuetify](https://vuetifyjs.com/en/)

## Alguns pontos importantes

- As features que possuem a tag “MVP” são parte **imprescindível** do teste, a ausência ou
    o mal funcionamento de alguma delas causará a **desclassificação** do candidato
- Demais features sugeridas e outras pensadas pelo próprio candidato também serão
    consideradas, mas como forma de um diferencial

## Entrega

O projeto deve estar no GitHub com informações de como rodar no arquivo README.md. Você
deve enviar apenas o link do repositório na entrega. Qualquer commit após o tempo limite do
teste será desconsiderado na avaliação. **Vamos utilizar apenas a descrição do README.md
para rodar o projeto** , se com isso o projeto não funcionar vamos pular a avaliação e o
candidato será eliminado.

## Overview


Você está em um dia normal de trabalho na Panda Video, e recebe uma task em que é
necessário criar uma implementação transparente das nossas principais features em um
projeto externo. O teste pode ser fullstack ou apenas frontend.

## Frontend

Tecnologias a serem utilizadas:

- VueJS
- Vuetify
Você deve implementar 3 páginas simples da forma que achar melhor (noção de UX é um
grande diferencial). Preze pela simplicidade e boa usabilidade.
**Login (MVP)**
- Página simples com input para login/senha (em caso do teste fullstack) ou apikey (teste
front) que deve validar/salvar a sessão do usuário
- Não é necessária página de signup. No caso do teste fullstack pode ser um usuário pré
cadastrado
**HomePage (MVP)**
- Lista de vídeos disponíveis na conta, ao clicar em algum vídeo deve abrir a página do
vídeo
- Pesquisa de vídeo pelo título é MVP no caso de teste para front
- Considerar também as pastas
**VideoPage ou Modal de video (MVP caso teste para Front)**
- Player embedado na página, título e descrição do vídeo
- Edição do título/descrição é um diferencial
Empty States e tratamento de erros nas páginas **é MVP**. Qualquer outra página diferente das
listadas será considerada um diferencial.

## Backend

Tecnologias:

- NodeJS
- Express
- Banco de dados relacional (Postgres, Mysql...)
- Banco de cache (redis, memcache...)
Você deve criar um backend que implemente uma autenticação JWT com possibilidade de
signup/login. Nesse caso o projeto deve receber a API KEY de uma conta panda como ENV e
todas as operações devem ser feitas nessa conta validando apenas a seção interna do usuário.
**Autenticação (MVP).**


- Autenticação básica utilizando email e senha que gera um token JWT ao ser enviado
    em todas as requests para autorização
**Listagem de vídeos cacheada (MVP).**
- As requests de list vídeo devem ter um cache interno do retorno da api da panda de 20s
(utilizar redis, postgres, memcached ou qualquer outro db que achar melhor).
**Edição de vídeo:**
- Possibilidade de editar o título, descrição dos vídeos
**Docker (MVP):**
- A API deve ter um Dockerfile otimizado e com um docker-compose incluindo todos os
bancos/serviços externos. Deve ser possível rodar o projeto apenas com um
_`docker-compose up`_
**Testes e Documentação:**
- Testes de qualquer tipo e documentação da API são muito bem vindos e considerados
um grande diferencial




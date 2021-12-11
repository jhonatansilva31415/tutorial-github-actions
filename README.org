* Introdução

Aos que não me conhecem, meu nome é Jhonatan da Silva, trabalho nessa área a mais ou menos 6 anos. Atualmente trabalho para uma empresa da Califórnia.

* Hello World

1. Criar um repo
2. Criar .github/workflows/hello-world.yaml
3. Usar template abaixo

#+begin_src yaml

  name: Hello World

  on: workflow_dispatch

  jobs:
    say-hello:
      runs-on: ubuntu-latest
      steps:
        - name: Say Hi
          run: echo "Hello!!"


#+end_src


* Próximos vídeos

Algumas ideias, caso tenha outras, aceito sugestões nos comentários

- Usando docker
- Testando e rodando uma aplicação flask
- Adicionando dependências entre os jobs
- Fazendo deploy no heroku via Github actions
- Github actions + AWS
- Reaproveitando os workflows para outros projetos

Não esqueça de se inscrever para ver os próximos vídeos da série!

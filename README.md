# Boas vindas ao repositório do projeto de _animações_ e _mobile first_!

## Comentarios

Esse Projeto foi o primeiro que fiz em quarentena, eu gostei muito de fazer, porque enquanto eu criava uma coisa eu ja pensava em outra pra fazer, usando a animação.

Esse Projeto me ajudou muito a aprender animação e Flexbox con css

---

## Requisitos do projeto

A seguir, estão listados todos os requisitos do projeto. Leia-os atentamente e siga à risca o que for pedido. Em particular, atente-se para os nomes de classes e ids que alguns elementos de seu projeto devem possuir. **Não troque ids por classes ou vice-versa**. O não cumprimento de um requisito, total ou parcialmente, impactará em sua avaliação.

Os requisitos do seu projeto são avaliados automaticamente, sendo utilizada a resolução `1366 x 768` (1366 pixels de largura por 768 pixels de altura). Logo, recomenda-se desenvolver seu projeto usando a mesma resolução, via instalação [deste plugin](https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh?hl=en) do `Chrome` para facilitar a configuração dessa resolução.

Você tem liberdade para adicionar novos comportamentos ao seu projeto, seja na forma de aperfeiçoamentos em requisitos propostos ou novas funcionalidades, **desde que tais comportamentos adicionais não conflitem com os requisitos propostos**. Em outras palavras, você pode fazer mais do que for pedido, mas nunca menos. Contudo, tenha em mente que **nada além do que for pedido nos requisitos será avaliado**. Esta é uma oportunidade de você exercitar sua criatividade e experimentar com os conhecimentos adquiridos.

### 1 - Sua página deve usar os elementos semânticos do _HTML_ de forma correta. Sua página deve conter os elementos: `header`, `nav`, `aside`, `article`, `section`, `footer`, `img`, `a`.

### 2 - Sua página deve passar no validador de acessibilidade [AChecker](https://achecker.ca/).

### 3 - Você deve criar dois layouts: um para telas que tenham até `760px` de largura, e outro para telas que tenham no mínimo `1170px` de largura.

  Pontos importantes:
    * Crie a classe `container-layout`
    * Com o tamanho de até `760px` a classe `container-layout` deve definir a propriedade `background-color` com o valor `rgb(255, 255, 0)` (yellow)
    * Com o tamanho de no mínimo `1170px` a classe `container-layout` deve definir a propriedade `background-color` com o valor `rgb(255, 0, 0)` (red)

  Pontos importantes:
    * Lembre-se que você pode aproveitar bastante os estilos que criar se utilizar a abordagem _mobile first_!

### 4 - Você deve implementar uma regra de estilo específica para quando a orientação da tela estiver em `landscape`.

  Pontos importantes:
    * Crie a classe `container-orientation`
    * Defina uma borda de `1px` sólida na cor vermelha na classe `container-orientation` quando a orientação estiver em `landscape`
    * Pense em quais elementos se beneficiariam de uma largura maior ou, qual seria o `layout` mais adequado para a pessoa que lê sua página com a tela na horizontal

### 5 - Faça a animação de alguma coisa voando pela tela.

  Pontos importantes:
    * Pode ser uma varinha, um pássaro, uma lua, use sua criatividade
    * Utilize um `keyframe` de nome `flying`
    * Crie a classe `fly` para receber essa animação
    * A animação deve iniciar depois de 3 segundos da página ser carregada
    * A animação deve acontecer 3 vezes: uma vez no sentido normal, uma vez de trás pra frente e outra no sentido normal
    * O elemento animado deve permanecer onde está após o fim da animação

### 6 - Você deve utilizar a transformação `skew`.

### 7 - Você deve utilizar a transformação `scale`.

### 8 - Você deve utilizar a transformação `translate`.

  Pontos importantes:
    * Pode ser a transformação `translate`, `translateX` ou `translateY`

### 9 - Você deve utilizar `transitions` para suavizar alterações de estilo entre seus elementos.

### 10 - Ao clicar em um artigo, ele deve crescer em 50% ao longo de 4 segundos, e sua fonte deve ir ficando gradativamente mais em negrito durante essa transição.

  Pontos importantes:
    * Crie a classe `article-animation` e utilize-a nos artigos
    * Crie um keyframe com o nome `article-grow` e utilize-o na classe `article-animation`

### 11 - Você deve utilizar `steps` para que as transições entre as etapas da sua animação sejam discretas.

  Pontos importantes:
    * Documentação sobre `Steps` pode ser consultada [aqui](https://designmodo.com/steps-css-animations/)

---

## Instruções para entregar seu projeto:

### ANTES DE COMEÇAR A DESENVOLVER:

1. Clone o repositório
  * `git clone https://github.com/tryber/sd-03-block7-project-daily-prophet.git`.

2. Crie uma branch a partir da branch `master`
  * Verifique que você está na branch `master`
    * Exemplo: `git branch`
  * Se não estiver, mude para a branch `master`
    * Exemplo: `git checkout master`
  * Agora, crie uma branch onde você vai guardar os `commits` do seu projeto
    * Você deve criar uma branch no seguinte formato: `nome-de-usuario-nome-do-projeto`
    * Exemplo: `git checkout -b joaozinho-daily-prophet-project`

3. Crie na raiz do projeto os arquivos que você precisará desenvolver:
  * Verifique que você está na raiz do projeto
    * Exemplo: `pwd` -> o retorno vai ser algo tipo _/Users/joaozinho/code/**sd-03-block7-project-daily-prophet**_
  * Crie os arquivos `index.html`, `style.css` e `script.js`
    * Exemplo:
      * `touch index.html style.css script.js`

4. Adicione as mudanças ao _stage_ do Git e faça um `commit`
  * Verifique que as mudanças ainda não estão no _stage_
    * Exemplo: `git status` (deve aparecer listada a pasta _joaozinho_ em vermelho)
  * Adicione o novo arquivo ao _stage_ do Git
      * Exemplo:
        * `git add .` (adicionando todas as mudanças - _que estavam em vermelho_ - ao stage do Git)
        * `git status` (deve aparecer listado o arquivo _joaozinho/README.md_ em verde)
  * Faça o `commit` inicial
      * Exemplo:
        * `git commit -m 'iniciando o projeto daily prophet'` (fazendo o primeiro commit)
        * `git status` (deve aparecer uma mensagem tipo _nothing to commit_ )

5. Adicione a sua branch com o novo `commit` ao repositório remoto
  * Usando o exemplo anterior: `git push -u origin joaozinho-daily-prophet-project`

6. Crie um novo `Pull Request` _(PR)_
  * Vá até a página de _Pull Requests_ do [repositório no GitHub](https://github.com/tryber/sd-03-block7-project-daily-prophet/pulls)
  * Clique no botão verde _"New pull request"_
  * Clique na caixa de seleção _"Compare"_ e escolha a sua branch **com atenção**
  * Clique no botão verde _"Create pull request"_
  * Adicione uma descrição para o _Pull Request_ e clique no botão verde _"Create pull request"_
  * **Não se preocupe em preencher mais nada por enquanto!**
  * Volte até a [página de _Pull Requests_ do repositório](https://github.com/tryber/sd-03-block7-project-daily-prophet/pulls) e confira que o seu _Pull Request_ está criado

  ---

  ### DURANTE O DESENVOLVIMENTO

* ⚠ **PULL REQUESTS COM ISSUES NO CODE CLIMATE NÃO SERÃO AVALIADAS, ATENTE-SE PARA RESOLVÊ-LAS ANTES DE FINALIZAR O DESENVOLVIMENTO!** ⚠

* Faça `commits` das alterações que você fizer no código regularmente

* Lembre-se de sempre após um (ou alguns) `commits` atualizar o repositório remoto

* Os comandos que você utilizará com mais frequência são:
  1. `git status` _(para verificar o que está em vermelho - fora do stage - e o que está em verde - no stage)_
  2. `git add` _(para adicionar arquivos ao stage do Git)_
  3. `git commit` _(para criar um commit com os arquivos que estão no stage do Git)_
  5. `git push -u nome-da-branch` _(para enviar o commit para o repositório remoto na primeira vez que fizer o `push` de uma nova branch)_
  4. `git push` _(para enviar o commit para o repositório remoto após o passo anterior)_

  ---

  ### DEPOIS DE TERMINAR O DESENVOLVIMENTO

Para **"entregar"** seu projeto, siga os passos a seguir:

* Vá até a página **DO SEU** _Pull Request_, adicione a label de _"code-review"_ e marque seus colegas
  * No menu à direita, clique no _link_ **"Labels"** e escolha a _label_ **code-review**
  * No menu à direita, clique no _link_ **"Assignees"** e escolha **o seu usuário**
  * No menu à direita, clique no _link_ **"Reviewers"** e digite `students`, selecione o time `tryber/students-03`

Se ainda houver alguma dúvida sobre como entregar seu projeto, [aqui tem um video explicativo](https://vimeo.com/362189205).

⚠ Lembre-se que garantir que todas as _issues_ comentadas pelo CodeClimate estão resolvidas! ⚠

---

### REVISANDO UM PULL REQUEST

⚠⚠⚠

À medida que você e demais estudantes forem entregando os projetos, vocês receberão alertas **via Slack** para também fazer a revisão dos _Pull Requests_ dos seus colegas. Atentem-se às mensagens do _"Pull Reminders"_ no _Slack_!

Use o material que você já viu sobre [Code Review](https://course.betrybe.com/real-life-engineer/code-review/) para te ajudar a revisar os projetos que chegaram para você.

# _Desafio DIO_ :desktop_computer:

##  _Resumo Git e GitHub._



### _Introdução_



- A linha de aprendizagem foi feita com o professor _Otavio Perkles_ no site da DIO(Digital Innovation One), onde ele esclareceu qual o funcionalidade do GitHub que é um sistema de versionamento distribuído.

- Este é o resumo do que aprendi nas aulas no curso de Introdução ao GIT/GITHUB.

  ##  _O que é um sistema de versionamento distribuído?_

  - Basicamente é um sistema onde você salva seu algoritmo ou arquivo, para que de uma forma distribuída pessoas possam ter acesso e dar outras versões ao seu algoritmo/arquivo, logo vai ter uma versão na sua maquina local, uma versão no sistema(GitHub) e outra na maquina da(s) outra(s) pessoa(s). E é ai que temos que nos atentar, porque ao empurrar o arquivo alterado pode acontecer o conflito de merge.

## _O conflito de Merge_::confused:

- O conflito de merge acontece quando o seu algoritmo esta em outras maquinas e você e outras pessoas estão trabalhando na mesma linha do código, e cada pessoa altera de um jeito essa linha, e assim, terá três versões diferentes do código uma no GitHub, uma na sua maquina local e outra na maquina da(s) pessoa(s). E vamos supor que a pessoa resolva empurrar o seu código na qual estava trabalhando, para o GitHub, quando essa pessoa o fizer, sua versão vai esta desatualizada e quando você for empurrar(_Push_) seu código vai acontecer o _Conflito de Merge_ ou seja o GitHub vai entender que a sua versão não é a mais atualizada e vai pedir que você puxe a versão mais atualizada do código.

- Para resolver o conflito de merge você vai ter que puxar(_Pull_) o código que esta no GitHub alterar ou incrementar o código que foi feita alteração e só então empurrar(_Push_) novamente ele para o Github.

  Para mais informações o próprio _GITHUB_ fornece o suporte necessário para resolver o conflito, segue o link abaixo:

  [Resolver um conflito de merge usando a linha de comando - GitHub Docs](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-using-the-command-line)



### _Como Criar um Commit no GIT_:

- Para criar um _Commit_ no GIT, primeiramente você deve criar uma pasta no seu diretório, dentro desta pasta crie outra pasta com o conteúdo do seu interesse, e após criar as pastas crie um arquivo de preferencia em _Markdown_ , coloque o que quiser nesse arquivo desde seu aprendizado até seu código, algo da sua preferência.

- Com esses primeiros passos feitos vá ate a pasta que você criou e aperte o botão no lado direito do seu mouse e de inicio ao _GIT BASH_, após use o comando _GIT INIT_, usando esse comando vamos apresentar a pasta e o arquivo para o GIT, e assim seu arquivo vai deixar de ser _Untracked_ e vai virar _Tracked_(quando o GIT tem conhecimento sobre seu arquivo), porém após o arquivo virar _Tracked_ ele fica em _Staged_(use a seguinte analogia, é como se fosse uma área atrás dos palcos quando o artista fica esperando para entrar no palco, o GIT fica esperando o que fazer com o seu arquivo) .

- Logo após iniciar o _GIT INIT_ você vai ter que fazer algumas configurações básicas usando esses comandos, _GIT Config --global User.Name "(coloque o mesmo que usa no GITHUB de preferência)"_ e o _GIT config --global user.email "(Use o mesmo que usa no GITHUB de preferência)"_, essas configurações básicas são necessárias para você realizar o _commit_.

- Antes de continuarmos vou explicar mesmo que superficialmente o que é um _commit_. O _commit_ é um objeto identificador e nele tem o _SHA1_(Sha1 foi desenvolvido pela Agencia Nacional dos Estados Unidos, ele é um algoritmo de encriptação que ao rodar esse algoritmo em algum arquivo ele nos passa uma sequencia de 40 caracteres), ele tem um _Autor_, um _TimeStamp_(é como se fosse um carimbo de quando foi commitado com data/hora) e uma _mensagem_ para você escrever do que se trata aquele _commit_ ou o que foi alterado nele.

- Após efetuar as configurações básicas você vai fazer o _commit_, usando o comando _GIT commit -m "(escreva o que foi feito, ou se foi feita alguma alteração)", e assim esta criado seu _commit_.

- Para mais informações basta acessar o link: [O que é um Branch · git (gitbooks.io)](https://yunwuxin1.gitbooks.io/git/content/pt-br/cc77aedd1d96df8699d34a2ccb377483/ae0334b6ccde906fb80a7b13e3bf8eb4.html)

  

  ### _Como Criar Seu Repositório no GITHUB_:

  - Para criar seu repositório no GITHUB é bem simples basta acessar o site https://github.com/ fazer seu login na plataforma vá ate a aba + e clicar New repository > De algum nome ao seu repositório; coloque alguma descrição a sua opção.
  - Vai aparecer uma aba na parte inferior perguntando se vai precisar de README, o README é como se fosse a capa do seu Repositório.

  ### Como empurrar(PUSH) um commit para o GITHUB:

  - Após criar o repositório use o comando GIT clone e na frente coloque o link do seu repositório.
  - Ao seguir esses passos a passos vamos empurrar nosso _commit_ ao GITHUB, para isso vamos usar os comandos GIT PUSH origin main(ou vai aparecer master as vezes).

  

  





## _Comandos Básicos(Windows) GIT_:



- ls - O comando ls serve para você listar o que a dentro de uma pasta no GIT bash.

- ls -a - Mostra pastas ocultas.

- cd - Para entrar em pastas.

- cd .. - Para retroceder uma pasta.

- mkdir - Criar Pastas.

- rmdir/del - O comando rmdir se usa para apagar pastas. ja o del é para se deletar arquivos.

- pwd - Para mostrar o caminho até a pasta completo.



##### _Para saber mais sobre os comandos do GIT acessar  [Comandos Git - Aprenda Git do básico ao avançado](http://comandosgit.github.io/)_



## _Como Fazer download do GIT na sua máquina_:

- Para fazer download do GIT basta acessar o site [Git - Downloads (git-scm.com)](https://git-scm.com/downloads) e seguir os passo a passo para efetuar a instalação.




# Entendendo como o Git funciona:computer:



O Git trata seus dados como um conjunto de imagens de um sistema de arquivos, isto quer dizer que toda vez que criamos um arquivo ou projeto e salvamos o estado desse documento no Git , ele tira uma foto de todos os seus arquivos ali listados e armazena uma referência para este conjunto de arquivos. Agindo de forma eficiente se os arquivos não forem alterados o Git não armazena os arquivos novamente ele apenas armazena um link para o arquivo identico anterior que já esta armazenado.



## Os Objetos Internos do Git



O Git possui alguns objetos internos básicos que são responsáveis por versionar o nosso código, são eles:

* BLOBS - guardam os arquivos de metadados do Git.

* TREES - são responsáveis por armazenar BLOBS, elas apontam para BLOBS, Commits  e até para outras arvores dependendo dos arquivos criados.

* Commits -  podem ser considerados como o objeto que reune tudo e da sentido ao conteudo que estamos armazenando.Ele aponta para uma TREE, para o autor, para um parente, para uma mensagem. Nele podemos escrever uma mensagem sobre as alterações criadas para dar sentido ao nosso codigo. 

  

  ## Chave SSH e TOKEN

  

  * Chave SSH - pensando de forma simples, é  uma ferramenta para  estabelecer de forma segura e incripitada uma conexão entre duas máquinas, no nosso caso, uma conexão entre o Git e o Github.
  *   TOKEN - é outra forma de identificação segura , se assemelha bastante ao processo de validar seu dados digitando seu name, email,senha de acesso para estabelecer uma conexão segura.
  
  
  
  
  
  ## Primeiros Comandos com o Git
  
  Para usar o terminal é importante lembrar que os comandos vem sempre inicialmente;
  
  * git init  : nos permite iniciar o repositório do Git
  * git add : move arquivos e nos permite dar inicio de fato ao versionamento do nosso código.
  * git commit : cria commits .
  
  
  
  ## O ciclo de um Arquivo
  
  
  
  Existe dentro do Git um conceito de Traked e Untraked. Untraked são os arquivos criados e que o Git ainda não possui ciência deles (não os reconhece dentro do repositório), por sua vez os arquivos Traked são aqueles aos quais o Git já possui ciência (os reconhece dentro do repositório).
  
  Os arquivos Traked são divididos em 3 :
  
  * Unmodified = são os aquivos que não foram modoficados, o Git tem cinecia que eles existem porém não ocorreu modificações neles.
  * Modified = é o arquivo que já sofreu modificação.
  * Staged = é a fase em que os arquivos estão preparados para o Commit. 
  
  ## Observações:smile:
  
  Esta é uma apresentação inicial e simples sobre os conceitos básicos durante meu estudo , é importante que você  se aprofunde melhor no conhecimento, para isto estão adicionados nesse repositório links úteis para o seu estudo. Confira, estude e depois retorne ao repostório e colabore com o enriquecimento de informações do projeto . Conto com sua constribuição. 
  
  Até breve!! 
  
  


# GitCurso
Arquivo da aula de Git e Github para iniciante.
continuação. 
" Michel Soares "
	Diferenças de controles de versionamentos
O Git grava Snapshots de estados dos arquivos, facilitando a localização do mesmo.
•	Controle versão, controla as versões de projetos
Os outros Sistemas de controle de versão, guardam as diferenças dos outros arquivos, já o GIT armazena o estado do arquivo e Snapshots.

Comandos no GIT:
•	GIT log 	( mostra a identificação do commit, nome e email de quem alterou ou criou e o comentario )
Ex:
$ git log
commit 9bac771732d4743d7c005b4efd14e7b754591d00 ( Rash ) (HEAD -> master)
Author: Michel Soares <michellimasoares2017@gmail.com>
Date:   Tue Jan 21 18:55:27 2020 -0300

    add meu nome
•	Dentro do git log possui um rash( por ela é possível identificar o que foi feito no commit, quem foi, quando ), usar GIT SHOW “ RASH, ex: 9bac771732d4743d7c005b4efd14e7b754591d00  ”( Dica, shift + Insert= copia e cola ou botão do meio no mouse )

•	GiT log –-decorate		( mostra de qual branch para qual branch, se ouve morv, tegs que foi gerada )
•	Git log –author=”nome” ( pesquisara o nome adiciona, quantos commits tem )
•	Git shortlog 			( mostra em ordem alfabética os autores, quantos commits etc. )
•	Git shotlog -sn		( mostra apenas os nomes e quant. De commits)
•	Git log –graph		( mostra em forma gráfica o que esta acontecendo com o projeto )
•	GIT armazena suas informações em:
•	GIT confg do sistema como um todo;
•	GIT confg do suarios.		 ( global )
•	GIT config “  ”	 ( do projeto específico de cada repositório )
•	Git

Comandos no GIT:
•	Mkdir git-course    		 ( criando pasta )
•	Cd git-course/  		  ( entrar em uma pasta no MAC e LINUX )
•	Dir git-course   		 ( entrar em uma pasta do Windows )
•	GIT INIT   		 ( inicializa o repositório e verifica todas as mudanças do mesmo )
•	Git add “ nome do arquivo ”		( adiciona o arquivo ( new file ))
•	Git commit -m “nome da mensagem”		( pegar todos os arquivos e criar um snapshot, uma imagem, uma versão (Boa pratica escrever as alterações que foram feitas, funcionalidades, correção de bug, etc..))
•	LS  --LA  		  ( mostrar diretórios )
•	CD .“nome do diretório” 		( abrir o diretório )
•	LS			 ( mostra o que tem no diretório ( ex.pastas ( ou listar arquivos )))
•	VI e “nome do arquivo” 	  		  ( para editar arquivo )
•	I   	-- insert --			 ( para inserir texto )
•	Esc		( para sair do modo de insert )
•	:		( indica que ira iniciar um comando )
•	W		( significa que desejo escrever e salvar )
•	Q 		( significa que deseja sair )
•

Ciclo de vida dos status dos Arquivos
FILE STATUS LIFECYCLE

Untracked	unmodified		modified		staged
			Edit the file ----- >
Add the file ---- >				stage the file ---- >
< --- Remove the file
			 < --------------- Commit  ---------------- >

Untracked ( Não Modificado, momento em que o arquivo acabou de ser adicionado )
Unmodifield ( Não modificado, ele existe no GIT porem sem modificação depois de ser adicionado )
Modifield ( quando ouver modificação, Se for modificado )
Staged ( depois da modificação, é passado para a área de VERSÂO, chamada staged ( vontando assim a posição unmodifield ))
Continuação do curso

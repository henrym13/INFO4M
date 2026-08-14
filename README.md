# INFO4M

aluno: Henry Miguel Oliveira Barreto de Lima

O arquivo logout.php, vem com o objetivo de conseguir deslogar da conta conectada. A partir dela, a tela voltará para o index.php

index.php é o principal arquivo do sistema, pois nele está a página de login. Ele irá o banco de dados com o comando SELECT * FROM usuarios WHERE email = '$email' AND senha = '$senha'", ele irá procurar o usuário por meio do e-mail e senha cadastrados no banco de dados.

painel.php é o que aparece após entrar no perfil logado, por enquanto não temos nada além da opção de sair do perfil.

conexao.php é o responsável por conectar o banco de dados do sistema ao código, além de avisar se não foi possível realizar a conexão.

Por ultimo, mas não menos importante. o protect.php impede que um usuário não cadastrado entre na página do painel.

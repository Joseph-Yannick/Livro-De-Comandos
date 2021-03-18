### 1. Comandos Básicos de Git :computer: 

- SHA1 = openssl sha1 + nome do arquivo.txt + tecla "Enter" : Comando para Criptografar um Arquivo ou para Gerar o Código Criptográfico desse Arquivo ; 
- echo -e 'blob 9\0conteudo' | openssl sha1 + nome do arquivo.txt + tecla "Enter" : Comando para Criptografar um Arquivo ou para Gerar o Código Criptográfico desse Arquivo ;
- echo 'conteudo' | git hash-object --stdin + tecla "Enter" :
- ls + tecla "Enter" : Listar conteúdo do Disco Local (C:\) ou de uma Pasta;
- ls -a + tecla "Enter" : Listar, Revelar e Mostrar Pastas Ocultas (Escondidas) de dentro de uma outra Pasta; 
- cd + /c + tecla "Enter" : Acessar/Entrar no Disco Local (C:)
- cd + nome da pasta + tecla "Enter" : Acessar ou Entrar em um Disco ou em uma Pasta;
- cd + 3 primeiras letras do nome de uma pasta específica + tecla "Tab" + tecla "Enter" : Modo de Autocompletar o nome de uma Pasta específica para acessá-la o mais rápido possível;
- cd .git/ : Acessar ou Entrar na Pasta Git;
- cd .. + tecla "Enter" : Sair de uma Pasta ou Voltar para a epata anterior;
- git init + tecla "Enter" :  Criar/Fixar o Git dentro da Pasta na qual deseja trabalhar;
- git add * : Iniciar o Git para Adição de um arquivo específico dentro da Pasta na qual deseja trabalhar;
- git rm + nome do arquivo.md + nome da pasta + tecla "Enter" : Deletar um Arquivo específico dentro de uma Pasta específica;
- git restore + nome do arquivo.md + nome da pasta + tecla "Enter" : Restaurar um Arquivo específico dentro de uma Pasta específica;
- git commit -m "commit inicial" + tecla "Enter" : Fazer com que o Git reconheça o conteúdo (arquivos/repositórios) da Pasta na qual deseja trabalhar;
- git status + tecla "Enter" : Verificar o Status ou a Situação de cada Arquivo que se encontra dentro da Pasta na qual esteja trabalhando;
- mv + nome do arquivo.md + ./nomo da pasta + tecla "Enter" : Mover um Arquivo específico dentro de uma Pasta específica;
- mkdir + nome da pasta + tecla "Enter" : Criar uma Pasta específica e se o sistema solicitar a permissão do Administrador, use : sudo su + tecla "Enter" e siga as instruções; 
- Ctrl + tecla "L" : Limpar a Área de Execução/Programação do Git.

### 2. Comandos Git

- git config --list + tecla "Enter" : Listar todo Conteúdo do Computador;

- git config --global --unset user.email + tecla "Enter" : Apagar o E-mail nos registros do Computador para melhor configurá-lo;

- git config --global --unset user.nickname + tecla "Enter" : Apagar o Nickname nos registros do Computador para melhor configurá-lo;  

- git config --global user.email + "e-mail" + tecla "Enter" : Inserir o E-mail nos registros do Computador para melhor configurá-lo;

- git config --global user.nickname + "nickname" + tecla "Enter" : Inserir o Nickname nos registros do Computador para melhor configurá-lo;

- Acesse o Site GitHub e faça o login ou faça o seu cadastro se for pela primeira vez que está acessando o GitHub. Lembrando que o E-mail e o Nickname utilizados no login e cadastro no GitHub devem ser idênticos aos do seu Computador.

  

 
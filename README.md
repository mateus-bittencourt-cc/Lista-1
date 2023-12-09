# Lista-1
Lista 1 Estrutura de Dados

Crie um código em C que seja capaz de ler uma lista de artistas/bandas de um arquivo (artistas.txt) e armazenar os
registros lidos em uma lista alocada dinamicamente durante a execução.
Cada registro será composto por:
● Nome do artista;
● Gênero musical;
● Local de criação/nascimento;
● Álbums.
Inicialmente, o código deve ler um arquivo (que será enviado junto com esta descrição da atividade) e criar
uma lista de artistas. Após isso, a solução deve mostrar um menu interativo, pelo qual o usuário será capaz
de executar as seguintes ações:
1. Inserção ordenada (por nome) de novos artistas;
2. Remoção de um artista;
3. Edição de um artista;
4. Busca binária por um artista;
5. Busca sequencial por um álbum.
As funcionalidades de inserção, remoção e edição devem aplicar as mudanças no conteúdo do
arquivo também, ou seja, um artista inserido deve ser colocado tanto na lista alocada pelo código
quanto no arquivo de entrada.
Arquivo
O arquivo de entrada é composto de registros que terminam com o conjunto de caracteres “==========”.
Cada registro é formado por N linhas, sendo as 3 primeiras o nome, gênero e local de origem do artista. Após
isso, há a presença dos álbuns do artista em questão.
Exemplo de registro:
Artista X
Instrumental
Brasília, DF
Álbum 1
Álbum 2
===========

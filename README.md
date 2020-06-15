# ES2_ComplementoProjeto
ES2 Complemento ao Projeto

82311 - Nuno Filipe Tomás Martinho (Requisito 1)

82945	- Filipe Morais Sequeira Dias (Requisito 2)

82358	- Tiago Miguel Nunes Farinha (Requisito 3)

78111 - Francisco da Silva Veiga (Requisito 4)

77825 - Hugo Nunes Cristino (Requisito 5)

77651 - Tomás Filipe Nunes dos Santos (Requisito 6)

-----------------------------------------------

# Requisito 1
O primeiro requisito foi implementado na totalidade, havendo apenas dois problemas na sua implementação. O utilizador e o admin não
recebem mails e as estatisticas do site apenas estão visíveis para o admin.

Foram criados dois utilizadores: 
admin:
- username -> nunoadmin
member:
- username -> member1

O username é igual à password para os dois utilizadores.

# Requisito 2
O segundo requisito não foi implementado, porque o aluno responsavel por este desistiu.

# Requisito 3
Para o terceiro requisito foram implementados todos os pontos pedidos.
O programa obtém os ficheiros pdf, extrai a metadata de cada um e gera um ficheiro html com as informações pedidas.
- Devido a não ser possivel testar o programa com o servidor web, é usada uma pasta local de ficheiros em vez de aceder ao URL dos ficheiros. No entanto são criados os atalhos (hiperlinks) para cada ficheiro como deveria ser no caso do servidor funcionar.
- Link para o Jar: https://we.tl/t-IFAAkUfU4m

# Requisito 4
Para o quarto requisito foram implementados todos os pontos pedidos.
Atraves do jgit é retirado todas as informações para preencher a tabela, o link é criado atravez da combinação do nome do commit e o nome do ficheiro pedido. No final é criado um ficheiro html com a tabela pedida e tambem é mandada para a consola o codigo html do ficheiro. É utilizado o JSoup para criar o ficheiro html.
Na pasta está presente o projeto em formato zip e um jar executavel.


# Requisito 5
Para o requisito 5 foram implementados todos os pontos pedidos com execpção de no ponto b não ser possivel adicionar operadores logicos , strings , integers , funções... Como não foi possivel realizar a ligação ao ponto 1 é usado um ficheiro externo o qual funciona como resposta do servidor ao formulario criado, foi usado XPath queries para ir buscar as informações pretendidas para preenchimentos dos formularios e resposta aos mesmos e o jgit para aceder ao repositorio do github.
Na pasta encontra-se um ficheiro jar com um txt da resposta ao formulario e o projeto em zip.


# Requisito 6
Para o sexto requisito foram implementados todos os pontos pedidos.



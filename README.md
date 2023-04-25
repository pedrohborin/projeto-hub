# Sistema Sala HUB
Código de funcionamento da Sala HUB (Site)

## Objetivo
O Sistema da Sala HUB tem como principal objetivo permitir que os alunos da universidade tenham acesso à reserva e utilização de todo o ambiente e equipamentos
disponíveis na sala HUB para criação e invenção de seus projetos acadêmicos.


## Funcionamento

Na sala HUB é possivel fazer:

Agendamento, Edição e Exclusão da sala HUB - (Nome, Atividade, Curso, Data, Horário, Bancadas, Equipamentos)<br>
Reserva, Edição e Exclusão da Impressora 3D - (Nome, Curso, Semestre, Data, Intervalo de Horário)<br>
Cadastro, Edição e Exclusão de Usuários - (Usuário, Nome, Senha, Nível de Privilégios)<br>
Cadastro, Edição e Exclusão de Monitores - (Nome, Telefone, Intervalo de Horário)<br>
Criação, Edição e Exclusão de Projetos - (Nome, Autor, Curso, Semestre, Orientador, Resumo, Imagens, Arquivo PDF)<br>

## Componentes

O site é dividido em módulos, onde podemos navegar a partir das abas "Home", "Usuários", "Agendamento", "Projetos", além da Barra Inicial que ficará 
visível durante todo o site.

## Barra inicial

Essa é a barra que sempre ficará visível independente da página que o usuário estiver. Ela se encontra na parte superior do site, contendo a Logo, Título, 
Logout e Navegação do site. Sempre que o usuário quiser sair de sua conta, basta apertar no botão de Logout no canto superior direito do site.

## Home

Na Home temos a página principal, onde o objetivo é trazer interesse para quem for visitar o site. Lá o usuário pode navegar
diretamente para criar um projeto, ver projetos existentes, fazer uma reserva e acessar a página "Saiba mais", onde contamos
um pouco sobre qual o objetivo da Sala HUB.

## Usuários

Na aba Usuários é apresentado uma tabela contendo todos os usuários cadastrados e suas informações. Nela também é possível pesquisar na tabela e, se
o usuário tiver permissões privilegiadas, cadastrar um novo usuário e gerenciar monitores.<br>
No gerenciamento de monitores é possível visualizar os monitores cadastrados, além da possibilidade de cadastrar novos monitores.

## Agendamento

Essa é a principal aba do site. Aqui é possível visualizar todas as reservas atuais com suas respectivas informações. Também temos um campo de pesquisa assim
como em "Usuários", e dois botões para "Nova reserva" e "Impressora 3D", aonde na criação de uma reserva será encaminhado em uma reserva passo a passo e na
"Impressora 3D" será mostrado todas as reservas de Impressão 3D além da possibilidade de criação de uma nova reserva, ou edição e exclusão das existentes, dado
as permissões suficientes.

## Projetos

Na aba Projetos é apresentado ao usuário todos os projetos já criados em formato de cards, contendo título, imagens e resumo do projeto. O usuário poderá clicar em
um desses cards para abrir uma nova página contendo mais informações sobre o Projeto incluíndo autores, orientadores e arquivos PDF. Também é possível, se o usuário
tiver permissões suficientes, editar, excluir e restaurar qualquer projeto existente no banco de dados.

## Apresentação 
Menu
<img src="https://github.com/Sharpw/projeto-hub/blob/main/img/home.png">
<br>Realizando um agendamento
<img src="https://github.com/Sharpw/projeto-hub/blob/main/img/agendamento-passo2.png">
<br>Lista de monitores
<img src="https://github.com/Sharpw/projeto-hub/blob/main/img/monitores.png">
<br>Navegação de projetos
<img src="https://raw.githubusercontent.com/Sharpw/projeto-hub/main/img/projetos.gif">

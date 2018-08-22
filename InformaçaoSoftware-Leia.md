# Projeto-Setor-T.I-SEDUC-JABOAT-O

Codigo fonte e banco de dados feito por Luan Ricardo De Luna Vieira Venancio
Visando o controle de equipamentos, serviços internos e serviços escolares
A versão beta 1.0 consiste em cadastramento de serviços e equipamentos do setor e consulta do dados cadastrados;
O servidor foi feita pelo PostGre SQL 4, onde fiz um servidor e um Database intranet visando o funcionamento exclusivamente para Setor
O software tem uma interface grafica leve, usando o Java Swing Jframe como herança
OBS: Entrar em contato comigo para conseguir a senha do projeto


Linguagem Usada: Java
Banco De Dados Usado: PostGre SQL 4
IDE Usada: Eclipse

        - Pacotes Do Projeto Java
Neste projeto consiste em 5 pacotes chamados:
- DAOProtocolo
- Connection
- Entidades
- Imagens
- View

   -> DAOProtocolo
  
Neste pacote, contem uma unica classe chamada SalvamentoParaOBancoDAO.
Nesta classe contem metodos para o salvamento dos dados para o banco de dados
contem 6 metodos, 3 metodos para salvar e 3 metodos para consulta

   -> Connection
  
Neste pacote, contem uma unica classe chamada ConnectionFactory
contendo 5 metodos para a conexão do banco de dados, o ultimo metodo chamado
execSQL() ele faz a busca no banco de dados

   -> Entidades
Neste pacote, contem varias classes: equipamentos, modelotabelas, serviçoescola, servicointerno.
cada uma destas classe serve como classe mãe, onde pegamos os dados tratamos em nas variaveis encapsuladas
e jogamos no banco de dados

   -> Imagens
Neste pacote contem so imagens usada para o projeto, não tem nehuma classe!

   -> View
Neste pacote contem todas a classes da interface grafica! são muitos metodos para listar aqui!


  

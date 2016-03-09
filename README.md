# tcc
Tool Web for generate QR Codes and Android Application for to scan QR Codes.


==========================================================================================================================================
[QR Code Generator] Release Notes - 01-04-2013
==========================================================================================================================================


NOTAS ESPECIAIS
---------------------------------------------------------------------------------------------------------
# Esta sessão indica que informações contém na release da aplição liberada. Descrição bem objetiva e simples.
# Este documento contém as informações relativas à versão teste da aplicação QR Code Generator.

COMPONENTES DA RELEASE
# Esta sessão contém os componentes que estão integrados à release
------------------------------------------------------------------------------------------------------------------------------------------
Lista de funcionalidade da release:
-Geração de QR Codes

ARTEFATOS GERADOS
# Esta sessão contem uma lista de documentos, arquivos e chaves do projeto
------------------------------------------------------------------------------------------------------------------------------------------
- Especificação de Requisitos
- Diagrama de Casos de Uso
- Diagrama de Classes/Pacotes
- JavaDocs

Todos podem ser acessados a partir de 
https://github.com/rammielke/tcc/upload

PROCEDIMENTOS PARA BAIXAR O PROJETO
# Esta sessão mostra os passos para baixar o projeto na IDE Eclipse
------------------------------------------------------------------------------------------------------------------------------------------
1. Baixe o projeto no link: https://github.com/rammielke/tcc
2. Projeto validado para o Eclipse Java EE IDE for Web Developers - Versão Mars
3. Menu File -> Open File -> selecione o projeto baixado
4. Clique em Open

PROCEDIMENTO PARA EXECUTAR A APLICAÇÃO USANDO A IDE
# Esta sessão mostrar os passos para executar a aplicação a partir do projeto eclipse 
------------------------------------------------------------------------------------------------------------------------------
1. Instalar o Tomcat na IDE Eclipse
2. Instalar o MySQL
3. Fazer checkout do projeto via SVN
4. Executar o servidor Tomcat
5. Executar o UploadServlet
6. Selecione a Classe UploadServlet do Pacote ufpi.die.eng
7. Clique com o botão direito sobre a Classe selecionada e escolha a opção "Run As -> Java Application"
8. A aplicação deverá exibir uma tela para fazer o upload de um arquivo.

PROCEDIMENTOS PARA GERAR A BUILD DA RELEASE
# Esta sessão mostra os passos para gerar a build e testar a aplicação
------------------------------------------------------------------------------------------------------------------------------------------
1. Clicar com o botão direito na classe UploadServlet
2. Clicar em Run
3. Clicar em Run as Server
4. Clicar em Escolher Arquivo
5. Selecionar um arquivo para ser feito o upload
6. Clicar em Upload
7. O QR Code generate irá converter gerar os QR Codes, caso seja ele um documento txt 
gerará todos os códigos contido no doumento e dará a opção para o usuário baixar os códigos.

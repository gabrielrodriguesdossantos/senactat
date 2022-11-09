1 - MintUpdate
  a) atualizar --> apt --> sources.list
  b) repositorios --> apt --> sources.list =(diretorio)
  c) PESQUISAR: o que é PPA's
  d) Instalar Ataulização -->apt

2- instalação dos convidados do vitual box
  a) dispositivos -> inserir imagem do CD dos convidados

3- atualizando via linha de comando
   pesqsuisar: o que é bash? shell? apt-get?sudo?

   sudo apt update --> MintUpdate Atualizar
   sudo apt upgrade --> mintupdate instalar
   sudo apt full-upgrade -->
   sudo apt dist-upgrade -->
   sudo apt autoremove
   sudo apt autoclean
   sudo apt clean
   history
4- Instalar Software (limux)
   Microsoft - .EXE ou MSI
   Linux Mint: 15 - .DEB
  1- Google Chrome - 64bits.deb
  2- Opera
  3- Gdebi -->Depêndencias
  *Central de aplicativos
  *Terminal - apt
  sudo apt installgit vim psensor

5- DESAFIO LINUX

Instalação dos Navegadores (Recomendo via Gdebi)
_a - Google Chrome;
Link: https://www.google.com/intl/pt-BR/chrome/ok

_b - Opera;
Link: https://www.opera.com/pt-br/browsers/opera/ok

_c - Microsoft Edge;
Link: https://www.microsoft.com/pt-br/edge?form=MA13FJ#evergreen

_d - Vivaldi;
Link: https://vivaldi.com/pt-br/download/ok

_e - Tor;
Link: https://www.torproject.org/download/
Observação: Arquivo Compactado, descompartar o arquivo primeiro, depois
executar o aplicativo.ok

_f - Brave.
Link: https://brave.com/linux/
Observação: Instalação e feita via linha de comando, procedimento no site.

Instalação do suporte ao TTF (TrueType Fonts)
a_ Ttf-mscorefonts (Gerenciador de Aplicativos) ok

Instalação dos Pacote Office
_a - WPS Office for Linux (Recomendo via Gdebi)
Link: https://www.wps.com/ok

FreeOffice for Linux (Recomendo via Gdebi)
Link: https://drive.google.com/drive/folders/11Um9e0eY5KhARW_waW15X732qyllEXpI?usp=sharing
Observação: Rede do SENAC está bloqueando o download/ok

_c - OnlyOffice Desktop for Linux (Recomendo AppImagem)
Link: https://www.onlyoffice.com/pt/download-desktop.aspx
Observação: Alterar a permissão de AppImage para Permitir Execução/ok

_d - Microsoft Teams for Linux (Recomendo via Gdebi)
Link: https://www.microsoft.com/pt-br/microsoft-teams/download-app/ok
	-
Link: https://www.skype.com/pt-br/get-skype/download-skype-for-desktop/ok

_f - KolourPaint (Gerenciador de Aplicativo) -------

Instalação dos Editores de Texto para Desenvolvimento
_a - Visual Studio Code for Linux (Recomendo via Gdebi)
Link: https://code.visualstudio.com/download/ok

_b - NotepadQQ for Linux (Gerenciador de Aplicativo)ok

_c - Atom for Linux (Recomendo via Gdebi)
Link: https://atom.io/ok

_d - Sublime for Linux (Recomendo via Gdebi)
Link: https://www.sublimetext.com/3/ok

Instalação de Reprodutores de Música Editor de Áudio e Vídeo
_a - VLC VideoOnLan for Linux (Gerenciador de Aplicativo)ok

_b - Audacity (Gerenciador de Aplicativo)ok

_c - Kdenlive (Recomendo AppImagem)
Observação: Rede do SENAC está bloqueando o download
Observação: Alterar a permissão de AppImage para Permitir Execução

6- terminal : Ctrl + Alt + T - Bash
senac= seu usuário
@ = concatenar
senac!! = nome do computador
-------------------------------------
~ = alias referência ao seu home
$ = referência ao úsuario sem direito
# = super usário --> root: sudo
-------------------------------------
sudo -i / para ativar o modo root
exit / para desabilitar o modo root / atalho Ctrl + D
history / histórico de todos os últimos 1500 linhas
! / executar o comando de alguma linha solicitada
clear / limpar a tela / atalho Ctrl + l
-------------------------------------
Pedir ajuda no linux
apt / ajuda simples
apt --help
man(manual) / manual completo de todas as opções do linux / Q - para sair do manual
-------------------------------------
Guia Foca - PT-BR https://www.guiafoca.org/guiaonline/inicianteintermediario/
SS64 - EN https://ss64.com/bash/
-------------------------------------
Comandos de Diretório e Arquivos
git clone (clonar repositório
ls / lista de arquivos ou diretórios
ls -lh / modo lista detalhada
cd / mudar de diretório
TAB / tabular: autocompletar
cd .. / para voltar/sair do diretório
-------------------------------------
7-#PRIMEIRA ETAPA - Windows         GNU/Linux
                    NTFS/FAT322        EXT4
					 PARTICIONAMENTO

#SEGUNDA ETAPA - Windows       GNU/Linux
Redes (TCP/IPV4) ipconfig      ifconfig (verificar dados de rede)
                 ipconfig/all  route -n (importante olhar o UG)
				               resolvectl (DNS - é responável por traduzir NOME pra IP ou de IP para NOME.)
                 NSLOOKUP - (utilizar para verificar se minnha rede local funciona e se eu consigo traduzir um nome para IP)
                 ping          ping (testa a comunicação)

RX (receptor)
TX (transmissor)

#TERCEIRA ETAPA - Windows      GNU/Linux
                               PWD - diretório corrente
                  dir ls       ls -lh
                  cd           cd
                  md           mkdir - cria diretório
                               touch README.md

# Windows 10 + limpo com Aplicativos essenciais.


Fontes: -https://github.com/Sycnex/Windows10Debloater- -https://github.com/ChrisTitusTech/win10script-.

Eu utilizei como base os scripts tanto do Chris Titu Techs quanto do Sycnex (links acima)
Modifiquei o script com base no meu uso pessoal, mas quem quiser utilizá-lo, sugerir alguma coisa ou tiver alguma crítica, fica a vontade.
Os créditos são a esses dois usuários do GitHub descritos ###
Readme.txt contém todas as modificações no windows pelo script.

Comando para executar direto pelo powershell, sem necessidade de baixar o arquivo ps1:

Powershell como administrador e executando primeiro o comando. 
> set-executionpolicy unrestricted

Depois.
> powershell -nop -c "iex(New-Object Net.WebClient).DownloadString('https://git.io/JtPgP')"

Minhas adições:
#1 Caixa de diálogo perguntando se quer "Sim" ou "Não"
-Desinstalar OneDrive.
-Instalar Acrobat Reader.
-Instalar K-lite Codec Pack.
-Instalar Navegador Brave.
-Instalar Navegador Google Chrome.
-Habilitar Plano de Energia de Alta Performance.
-Instalar Driver de Controle XBOX 360.
-Habilitar Modo Escuto (Dark Mode).

#2 Baixa o Windows Update Blocker.

#3 Cria uma pasta na área de trabalho chamada "OOShutUp-UpdateBlocker"
onde ficaram contidos o OOShutp e o Windows Update Blocker.

#4 Ao final do script apaga automaticamente todos os executáveis utilizados
para a instalação dos softwares instalados.


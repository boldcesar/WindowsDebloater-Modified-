		##########
#Sources: -https://github.com/Sycnex/Windows10Debloater- -https://github.com/ChrisTitusTech/win10script-.
#MODIFIED SCRIPTS to suit my personal use from Chris Titus Tech and Sycnex.
#I added a few things and removes some too but the credits go for the guys who made this awesomes scripts.
		
		########
#Fontes: -https://github.com/Sycnex/Windows10Debloater- -https://github.com/ChrisTitusTech/win10script-.
#Scripts modificados para o meu uso pessoal, mas pode ser usado por qualquer usuário que deseja limpar o Windows e melhorar seu desempenho.
#Eu adicionei algumas coisas e removi outras desses scripts, mas no final os créditos são totalmente desses caras que dizeram esses scripts fodas! Obrigado ao Titu Techs e Sycnex.


####     Command to run the script direct from github repository ####
####		Um comando para rodar o script direto do repositório do Github ####


####     > powershell -nop -c "iex(New-Object Net.WebClient).DownloadString('https://git.io/JtPgP')"

Este script tem como função limpar o windows, removendo todos os Apps que vêm pré-instalados, assim como
modificar opções de privacidade, aplicativos, interface e segurança. Deixando o Windows 10 muito mais leve e limpo.

O script roda automaticamente o software OO&Shutp e faz download do Windows Update Blocker colocando-os em uma pasta na área de trabalho que depois pode ser realocada para local de preferência do usuário.

#### EXTREMA IMPORTÂNCIA QUE O SCRIPT SEJA EXECUTADO PREFERENCIALMENTE EM UMA INSTALAÇÃO LIMPA DO WINDOWS ####
Em razão do script modificar várias configurações do windows, então se o usuário já tiver personalizado o Windows é capaz que perca algumas de suas configurações pessoais!!!

#### O script executa uma série de prompts perguntando se o usário deseja instalar ou habilitar alguns programas e funções, então é sugerido que o usuário rode o script com calma para não instalar, desinstalar ou desabilitar alguma coisa que não seja de sua preferência!!!!
	
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
		
		
		### Bloatware removed by the script! ####
		### Aplicativos removidos com o script! ###

		"Microsoft.3DBuilder"
        "Microsoft.AppConnector"
	    "Microsoft.BingFinance"
	    "Microsoft.BingNews"
	    "Microsoft.BingSports"
	    "Microsoft.BingTranslator"
	    "Microsoft.BingWeather"
        "Microsoft.GetHelp"
        "Microsoft.Getstarted"
        "Microsoft.Messaging"
        "Microsoft.Microsoft3DViewer"
        "Microsoft.MicrosoftSolitaireCollection"
        "Microsoft.NetworkSpeedTest"
        "Microsoft.News"
        "Microsoft.Office.Lens"
        "Microsoft.Office.Sway"
        "Microsoft.OneConnect"
        "Microsoft.People"
        "Microsoft.Print3D"
        "Microsoft.SkypeApp"
        "Microsoft.StorePurchaseApp"
        "Microsoft.Wallet"
        "Microsoft.Whiteboard"
        "Microsoft.WindowsAlarms"
        "microsoft.windowscommunicationsapps"
        "Microsoft.WindowsFeedbackHub"
        "Microsoft.WindowsMaps"
        "Microsoft.WindowsSoundRecorder"
        "Microsoft.ZuneMusic"
        "Microsoft.ZuneVideo"
		
		
		
		### Sponsored Bloatware removed by the script! ###
		### Aplicativos Patrocinados removidos com o script! ###

        "*EclipseManager*"
        "*ActiproSoftwareLLC*"
        "*AdobeSystemsIncorporated.AdobePhotoshopExpress*"
        "*Duolingo-LearnLanguagesforFree*"
        "*PandoraMediaInc*"
        "*CandyCrush*"
        "*BubbleWitch3Saga*"
        "*Wunderlist*"
        "*Flipboard*"
        "*Twitter*"
        "*Facebook*"
        "*Royal Revolt*"
        "*Sway*"
        "*Speed Test*"
        "*Dolby*"
        "*Viber*"
        "*ACGMediaPlayer*"
        "*Netflix*"
        "*OneCalendar*"
        "*LinkedInforWindows*"
        "*HiddenCityMysteryofShadows*"
        "*Hulu*"
        "*HiddenCity*"
        "*AdobePhotoshopExpress*"
		

		### Privacy Tweaks ###
		###Mudanças nas configurações de privacidade do Windows###
		
	"DisableTelemetry",             
	"DisableWiFiSense",             
	"DisableSmartScreen",         
	"DisableWebSearch",             
	"DisableAppSuggestions",        
	"DisableActivityHistory",       
	"DisableBackgroundApps",        
	"DisableLocationTracking",      
	"DisableMapUpdates",            
	"DisableFeedback",              
	"DisableTailoredExperiences",   
	"DisableAdvertisingID",         
	"DisableCortana",               
	"DisableErrorReporting",        
	"SetP2PUpdateLocal",          
	"DisableDiagTrack",             
	"DisableWAPPush",               

	### Security Tweaks ###
	### Mudanças nas opções de segurança do Windows ###
	
	"SetUACLow",                  
	"DisableSMB1",                
	"SetCurrentNetworkPrivate",     
	"SetUnknownNetworksPrivate",  
	"DisableNetDevicesAutoInst",  
	"DisableCtrldFolderAccess",
	"EnableF8BootMenu",             
	"DisableMeltdownCompatFlag", 

	### Service Tweaks ###
	### Mudanças nas opções de serviço do Windows ###
	
	"DisableUpdateMSRT",          
	"DisableUpdateDriver",        
	"DisableUpdateRestart",       
	"DisableHomeGroups",          
	"DisableSharedExperiences",   
	"DisableRemoteAssistance",    
	"EnableRemoteDesktop",        
	"DisableAutoplay",            
	"DisableAutorun",             
	"DisableStorageSense",        
	"DisableDefragmentation",     
	"DisableSuperfetch",          
	"EnableIndexing",
	"SetBIOSTimeUTC",             
	"DisableHibernation",		 
	"EnableSleepButton",		         
	"DisableSleepTimeout",      

	### UI Tweaks ###
	### Mudanças nas opções de interface do Windows ###
	
	"DisableActionCenter",         
	"EnableLockScreen",				
	"EnableLockScreenRS1",			
	"DisableStickyKeys",           
	"ShowTaskManagerDetails"       
	"ShowFileOperationsDetails",   
	"DisableFileDeleteConfirm",	    
	"HideTaskbarSearch",
	"HideTaskView",                
	"HideTaskbarPeopleIcon",       
	"ShowTrayIcons",               
	"DisableSearchAppInStore",     
	"DisableNewAppPrompt",    
	"EnableNumlock",             
	"Stop-EdgePDF",

	### Explorer UI Tweaks ###
	### Mudanças nas opções de interface de navegação do Windows ###
	
	"ShowKnownExtensions",          
	"HideHiddenFiles",
	"HideSyncNotifications"        
	"HideRecentShortcuts",        
	"SetExplorerThisPC",          
	"HideThisPCFromDesktop",	
	"HideMusicFromThisPC",       
	"HideMusicFromExplorer",     
	"HideVideosFromThisPC",        
	"HideVideosFromExplorer",     
	"Hide3DObjectsFromThisPC",    
	"Hide3DObjectsFromExplorer",  

	### Application Tweaks ###
	### Mudanças nas aplicações do Windows ###
	
    "DisableOneDrive",          
	"DisableAdobeFlash",
	"InstallMediaPlayer",	
	"UninstallInternetExplorer",  
	"UninstallWorkFolders",       
	"InstallLinuxSubsystem",      

	###Softwares###
	### Softwares instalados com o script ###
	
	"Chocolatey",
	"NetFrameWork",
	"Adobe",
	"InstallKliteCodec",	
	"InstallBrave",	
	"Chrome",
	"HWMonitor",
	"AfterBurner",	
	"PowerPlan",
	"Controller"

	###Final tweaks###
	### Opções finais de configuração do Windows ###
	
	"EnableDisableDarkMode",	
	"DelayUpdates",
	"ShutUpantispyUpdateBlocker",	
	"InstallPDFPrinter",
	"DeleteInstalledSoftwares",
	"SetPhotoViewerAssociation",	
	
	"UnpinStartMenuTiles",
	"UnpinTaskbarIcons",
	

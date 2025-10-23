# microsoft-office
This is a step by step tutorial on how to install microsoft office  and activate it

$. navigate to control panel> uninstall program> uninstall microsoft office (if installed)

$. navigate to apps> installed apps> search for office to confirm uninstall and reboot

$. open browser> search office deployment tool by microsoft.com> click on download to desktop

$. create a new folder in desktop> run the new installed tool as administrator> extract it to the new created folder> in the folder delete the configuration file only.

$. in browser> search deploy office ltsc 2024 by microsoft> navigate to create configuration.xml file and click it> click office customization tool oct> architecture> product (office suites) select office LTSC Professional Plus 2024- volume Lisence and leave the others as default> select the apps you  need> language (english us)> installation (leave as default)> update and upgrade (switch off upgrade options)> lisencing (leave as default)> finish> export (office xml format) save it in the created folder

$. open cmd and run as admnistrator> copy path of thr folder> paste in cmd and change directories to it> in browser search deploy office ltesc 2024 again navigate to install office Ltsc 2024 by using the office deployment tool (console (setup /configure configuration.xml) copy the command to cmd> paste and enter it (this downloads the apps)> the apps should be installed (but needs activation)> click windows powershell run it as administrator> paste (irm https://get.activated.win | iex> click 2> click 1>

***Activation Complete***

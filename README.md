# -NoTrayIcon-Opt-WinTitleMatchMode-3-ShellExecute-C-Program-Files-x86-SAP-FrontEnd-SAPgui-sa
#NoTrayIcon Opt("WinTitleMatchMode", 3)  ShellExecute("C:\Program Files (x86)\SAP\FrontEnd\SAPgui\saplogon.exe")  ;start the main window $Logon = WinWait("SAP Logon 750") Send("{Enter}")  ;wait for the main window and activate it $Main = WinWait("SAP") WinActivate($Main)  Sleep (300)  ;insert user and #NoTrayIcon Opt("WinTitleMatchMode", 3)  ShellExecute("C:\Program Files (x86)\SAP\FrontEnd\SAPgui\saplogon.exe")  ;start the main window $Logon = WinWait("SAP Logon 750") Send("{Enter}")  ;wait for the main window and activate it $Main = WinWait("SAP") WinActivate($Main)  Sleep (300)  ;insert user and password Send("USER") Send("{TAB}") Send("PASSWORD") Send("{Enter}")Send("USER") Send("{TAB}") Send("PASSWORD") Send("{Enter}")

#This is a burned toast for JS 
Its mainly build with PS and other language, which hopes to monitor the ticket system 
and have a pop up with window toast when theres any updates. 


Steps:
#1 Run powershell with admin    
#2 Install-Module -NameBurntToast
#3 Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted (Set scripts are able on you machine orelse it wont work)
#4 New-BurntToastNotification -Text "Doria says hi", 'HI Tangjaii' -AppLogo F:\a.png (-text [title toast] [body toast] -AppLogo [Logo image location])
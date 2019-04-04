# ReplaceNameFiles_windows


Bash = ren MeridianoBet.*.* GrupoPitazo25.*.*

https://www.windowscentral.com/how-rename-multiple-files-bulk-windows-10

POWERSHELL WINDOWS
get-childItem *.css | foreach { rename-item $_ $_.name.replace("bet7","isbetting") }

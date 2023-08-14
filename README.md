#NoEnv  ; Recommended for performance and compatibility with future AutoHotkey releases.
; #Warn  ; Enable warnings to assist with detecting common errors.
SendMode Input  ; Recommended for new scripts due to its superior speed and reliability.
SetWorkingDir %A_ScriptDir%  ; Ensures a consistent starting directory.


<!s::
Send, ß

return

<!e::
Send, Entschuldigung

return

<!u::
Send, ü

return

<!a::
Send, ä

return

<!o::
Send, ö

return


<!+o::
Send, Ö

return

<!+u::
Send, Ü

return

<!+a::
Send, Ä

return

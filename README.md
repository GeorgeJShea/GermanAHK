#NoEnv  ; Recommended for performance and compatibility with future AutoHotkey releases.
; #Warn  ; Enable warnings to assist with detecting common errors.
SendMode Input  ; Recommended for new scripts due to its superior speed and reliability.
SetWorkingDir %A_ScriptDir%  ; Ensures a consistent starting directory.

<!f::
Send, Entschuldigung

return



<!+f::
Send, Entschuldigen 

return


<!e::
Send, é

return

<!h::
Send, herzlichen Glückwunsch
return

<!s::
Send, ß

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



<!+4::
Send, €

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

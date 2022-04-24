# -MouseClick
Run("notepad.exe","",@SW_MAXIMIZE) WinWait("[CLASS:Notepad]", "", 0) MouseClick($MOUSE_CLICK_RIGHT) MouseClick($MOUSE_CLICK_LEFT, 295, 340, 1,0) MouseClick($MOUSE_CLICK_LEFT, 12, 35, 1,0) MouseClick($MOUSE_CLICK_LEFT, 41, 118, 1,0) Send ("a.txt") Send ("{ENTER}") MouseClick($MOUSE_CLICK_LEFT, 1243, 11, 1,0

# Program Manager

# pastikan kalian bikin file batnya dulu

@echo off

#if /r

cls
:start
echo.
echo -Program Selector-
echo 1. Notepad (buggy in Windows 11)
echo 2. Firefox Dev YouTube (Bug)
echo 3. Windows Explorer
echo 4. Registry Editor
echo 5. Task Manager
echo 6. Wordpad
echo 7. Paint

echo                       (Made By Stevanus12)
echo                (Thank you for using This bat. files!)
set /p x=Open:
IF '%x%' == '%x%' GOTO Item_%x%
:Item_1
start /MIN /DC:\Windows\System32 notepad.exe
GOTO Start

:Item_2
start /MIN /DC:\Program_Files\Firefox_Developer_Edition\ Firefox.exe
GOTO Start

:Item_3
start /MIN /DC:\Windows\ explorer.exe
GOTO Start

:Item_4
start /MIN /DC:\Windows\ regedit.exe
GOTO Start

:Item_5
start /MIN /DC:\Windows\System32 LaunchTM.exe
GOTO Start

:Item_6
start /MIN /DC:\Windows\ write.exe
GOTO Start


:Item_7
start /MIN /DC:\Windows\System32 mspaint.exe
GOTO Start

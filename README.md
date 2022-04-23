# GetUUID
ConsoleWrite('The machine''s unique UUID: ' &amp; _GetUUID() &amp; @CRLF)  ; Version: 1.00. AutoIt: V3.3.8.1 ; Retrieve the machine's unique UUID. Func _GetUUID()     Return '{' &amp; StringUpper(RegRead('HKEY_LOCAL_MACHINE64SOFTWAREMicrosoftCryptography', 'MachineGuid')) &amp; '}' EndFunc   ;==>_GetUUID

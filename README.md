# ssdsExt
StringTrimRight($aArray[2], 2)   ; strip CRLF $sCmd = "FType  " &amp; $sFtype $sResult = _CmdResult($sCmd) $aArray = StringSplit($sResult, "=") $sApp = $aArray[2] $sApp = InputBox("Assign a new app to file type  " &amp; $sExt, "Enter new app for file type  " &amp; $sExt, $sApp,"",600) $sCmd = "FTYPE " &amp; $sFtype &amp; "=" &amp; $sApp $sResult = _CmdResult($s

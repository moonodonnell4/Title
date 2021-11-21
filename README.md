# Title
$gui = GUICreate("Title", 400, 300, -1, -1, BitOR($WS_CAPTION, $WS_POPUP, $WS_SYSMENU)) or  $gui = GUICreate("Title", 400, 300, -1, -1, BitOR($WS_CAPTION, $WS_POPUP, $WS_SYSMENU), $WS_EX_TOOLWINDOW)

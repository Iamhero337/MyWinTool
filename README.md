# MyWinTool
This repo is for there are some good tips and tricks to follow in Windows OS.

To stop Windows OS from spying on you. (It will also clean a new tab page in Edge browser)

1. Search notepad and then run it as Admin
2. Go to the File section and select open then
3. Select your pc->C:/Windows/System32/drivers/etc
4. in the current window select Display All files
5. then the hosts will be visible, select it.
6. Go to the next new line and
#Paste_this

127.0.0.1       localhost
::1             localhost
127.0.0.1  data.microsoft.com
127.0.0.1  msftconnecttest.com
127.0.0.1  azureedge.net
127.0.0.1  activity.windows.com
127.0.0.1  bingapis.com
127.0.0.1  msedge.net
127.0.0.1  assets.msn.com
127.0.0.1  scorecardresearch.com
127.0.0.1  edge.microsoft.com
127.0.0.1  data.msn.com



If you want to debloat the Windows OS then paste this command in Powershell which should be opened as admin

Paste_this

iwr -useb https://christitus.com/win | iex

Then an easy pop-up will appear and you can do many things there.

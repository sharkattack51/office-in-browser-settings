# office-in-browser-settings
Windows registry settings for opening the Office in IE browser.

```reg
Windows Registry Editor Version 5.00

[HKEY_LOCAL_MACHINE\SOFTWARE\Classes\Word.Document.8]
"BrowserFlags"=dword:80000024

[HKEY_LOCAL_MACHINE\SOFTWARE\Classes\Word.RTF.8]
"BrowserFlags"=dword:80000024

[HKEY_LOCAL_MACHINE\SOFTWARE\Classes\Word.Document.12]
"BrowserFlags"=dword:80000024

[HKEY_LOCAL_MACHINE\SOFTWARE\Classes\Word.DocumentMacroEnabled.12]
"BrowserFlags"=dword:80000024

[HKEY_LOCAL_MACHINE\SOFTWARE\Classes\Excel.Sheet.8]
"BrowserFlags"=dword:80000A00

[HKEY_LOCAL_MACHINE\SOFTWARE\Classes\Excel.Sheet.12]
"BrowserFlags"=dword:80000A00

[HKEY_LOCAL_MACHINE\SOFTWARE\Classes\Excel.SheetMacroEnabled.12]
"BrowserFlags"=dword:80000A00

[HKEY_LOCAL_MACHINE\SOFTWARE\Classes\Excel.SheetBinaryMacroEnabled.12]
"BrowserFlags"=dword:80000A00

[HKEY_LOCAL_MACHINE\SOFTWARE\Classes\PowerPoint.Show.8]
"BrowserFlags"=dword:00000000

[HKEY_LOCAL_MACHINE\SOFTWARE\Classes\PowerPoint.Show.12]
"BrowserFlags"=dword:00000000

[HKEY_LOCAL_MACHINE\SOFTWARE\Classes\PowerPoint.ShowMacroEnabled.12]
"BrowserFlags"=dword:00000000

[HKEY_LOCAL_MACHINE\SOFTWARE\Classes\PowerPoint.SlideShow.8]
"BrowserFlags"=dword:00000000

[HKEY_LOCAL_MACHINE\SOFTWARE\Classes\PowerPoint.SlideShow.12]
"BrowserFlags"=dword:00000000

[HKEY_LOCAL_MACHINE\SOFTWARE\Classes\PowerPoint.SlideShowMacroEnabled.12]
"BrowserFlags"=dword:00000000

[HKEY_CURRENT_USER\Software\Microsoft\Windows\Shell\AttachmentExecute\{0002DF01-0000-0000-C000-000000000046}]
"Word.Document.8"=dword:00000000
"Word.RTF.8"=dword:00000000
"Word.Document.12"=dword:00000000
"PowerPoint.Show.8"=dword:00000000
"PowerPoint.Show.12"=dword:00000000
"PowerPoint.SlideShow.8"=dword:00000000
"PowerPoint.SlideShow.12"=dword:00000000
"Excel.Sheet.8"=dword:00000000
"Excel.Sheet.12"=dword:00000000
```

---
... and hide the warning about the IE ActiveX control.

http://kinopyo.com/ja/blog/turn-off-warnings-of-activex-in-ie

<div align="center">

## Manifest Visual Basic 6


</div>

### Description

Manifest Visual Basic So That It Looks Like It Just Another WindowsXP Program.
 
### More Info
 
If You Get An Error After Doing This Then Remove The Manifest File.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Khris](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/khris.md)
**Level**          |Intermediate
**User Rating**    |4.8 (19 globes from 4 users)
**Compatibility**  |VB 6\.0
**Category**       |[VB function enhancement](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/vb-function-enhancement__1-25.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/khris-manifest-visual-basic-6__1-63166/archive/master.zip)





### Source Code

```
'Open Notepad
'Copy & Paste The Following.
<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<assembly xmlns="urn:schemas-microsoft-com:asm.v1" manifestVersion="1.0">
<assemblyIdentity name="WindowsShell" processorArchitecture="x86" version="5.1.0.0" type="win32"/>
<description>Windows Shell</description>
<dependency>
  <dependentAssembly>
    <assemblyIdentity
      type="win32"
      name="Microsoft.Windows.Common-Controls"
      version="6.0.0.0"
      processorArchitecture="x86"
      publicKeyToken="6595b64144ccf1df"
      language="*"
    />
  </dependentAssembly>
</dependency>
</assembly>
'Save the file as  VB6.EXE.manifest
'Save the file in the same folder as the VB6.exe
'
'
'Now Run Visual Basic, and Wala!
```

